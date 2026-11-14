<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9usyqbvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pin-duty-free" /></template>
<style>
.s9usyqbvi {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.75 7.25h4.5V7q0-1.125-.562-1.687T12 4.75Q9.75 4.75 9.75 7zm6 0h.91q3.008 0 3.353 2.988l.894 7.75q.174 1.503-.833 2.632t-2.519 1.13H6.445q-1.513 0-2.519-1.13t-.833-2.632l.894-7.75Q4.332 7.25 7.34 7.25h.91V7q0-3.75 3.75-3.75q1.875 0 2.813.938q.937.937.937 2.812z");
}

</style>
