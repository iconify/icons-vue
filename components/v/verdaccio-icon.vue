<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":216};
const content = `<path class="o2uwhp26h"/><path class="f2_-pbbip"/><path class="gi830-zil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:verdaccio-icon" /></template>
<style>
.f2_-pbbip {
  fill: var(--svg-color--cd4000, #cd4000);
  d: path("M128 51.2V40.229l38.4-.005l5.481-10.967h-25.595V18.286l31.085-.005l3.658-7.314l-16.458.004V0H256l-25.6 51.2z");
}

.gi830-zil {
  fill: var(--svg-color--4a5e3f, #4a5e3f);
  d: path("m62.693 10.971l87.675 175.932l-9.02 17.897h-26.687L17.746 10.971z");
}

.o2uwhp26h {
  fill: var(--svg-color--405236, #405236);
  d: path("m217.6 76.8l-69.486 138.971h-40.228L0 0h69.486L128 117.029L148.114 76.8z");
}

</style>
