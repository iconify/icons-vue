<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b1e94ubzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:spiral-two-tone" /></template>
<style>
.b1e94ubzx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 13C14 11.8954 13.1046 11 12 11C10.8954 11 10 11.8954 10 13C10 15.2091 11.7909 17 14 17C16.2091 17 18 15.2091 18 13C18 9.6863 15.3137 7 12 7C8.6863 7 6 9.6863 6 13C6 17.4183 9.5817 21 14 21C18.4183 21 22 17.4183 22 13C22 7.4772 17.5228 3 12 3C6.4772 3 2 7.4772 2 13");
}

</style>
