# NAME

DBIx::Schema::DSL::Dumper - DBIx::Schema::DSL generator

# SYNOPSIS

    use DBIx::Schema::DSL::Dumper;

    print DBIx::Schema::DSL::Dumper->dump(
        dbh => $dbh,
        pkg => 'Foo::DSL',
        default_not_null => 1,
        default_unsigned => 1,
    );

# DESCRIPTION

This module generates the Perl code to generate DBIx::Schema::DSL.

# WARNING

IT'S STILL IN DEVELOPMENT PHASE.
I haven't written document and test script yet.

# SEE ALSO

[DBIx::Schema::DSL](https://metacpan.org/pod/DBIx::Schema::DSL), [Teng::Schema::Dumper](https://metacpan.org/pod/Teng::Schema::Dumper)

# LICENSE

Copyright (C) Kenta, Kobayashi.

This library is free software; you can redistribute it and/or modify
it under the same terms as Perl itself.

# AUTHOR

Kenta, Kobayashi <kentafly88@gmail.com>