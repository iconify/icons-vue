<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hmm-jpbyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:quick-bible" /></template>
<style>
.hmm-jpbyb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 42.138h39M24 36.994V5.862m-9.533 8.345h19.066M20.98 40.438L4.953 39.65l.615-4.542Zm-2.565-2.99l-9.86-5.599m18.465 8.589l16.028-.788l-.615-4.542Zm2.565-2.99l9.86-5.599");
}

</style>
