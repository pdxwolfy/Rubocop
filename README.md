LS .rubocop.yml files

I have 3 .rubocop.yml files here. They correspond to the 101 Lesson 2, 101 Lesson 4, and 120 Lesson 2 .rubocop.yml files.

The files declare only those Cops we want to activate - I've think I'm very, very close to what things must have been like as of last December. I use only Cops that were defined in Rubocop 0.35.0, which was current in December of last year.

The files are known to work with Rubocop 0.46.0.

I've tried running these against the same code shown in the Rubocop run throughs in the lessons; that's easier to say than to do, though. However, I'm confident that I'm catching the same errors that get caught in the videos.

The files are set up so that new versions of Rubocop won't break anything unless they eliminate or rename cops; even then, we should only get warnings. If we insist that people use Rubocop 0.46.0, that becomes less of a concern.

At some point, we will probably want to do this again and "catch up" to modern Ruby and Rubocop.

Note that students using Ruby 2.3 or higher should probably set the TargetRubyVersion so doesn't Rubocop doesn't complain about things like `<<~` and `&.`.
