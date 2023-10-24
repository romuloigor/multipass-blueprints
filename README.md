# multipass-blueprints
Blueprints for https://multipass.run

#multipass launch lts --name vm01 --network en0 --mem 2G --disk 8G --cpus 2

export MULTIPASS_BLUEPRINTS_URL=https://github.com/romuloigor/multipass-blueprints

multipass launch \
  --cloud-init https://raw.githubusercontent.com/romuloigor/multipass-blueprints/main/cloud-init/microk8s.yaml \
  --network en0