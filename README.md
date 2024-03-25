This repository is a placeholder for your Nixserver repository secrets. Your actual secrets are stored at the root of
your Nixserver repository in a directory called `secrets`.

When Nixserver builds your service, we substitute the placeholder with the actual path to your encrypted secrets. We
have to do this due to a limitation in the way you can reference flake inputs in Nix.
