<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zg6rtxbmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:navigation-up-right" /></template>
<style>
.zg6rtxbmn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4.3977 8.98L19.2337 4.03C19.6883 3.88 20.1207 4.31 19.9691 4.77L15.0229 19.6C14.859 20.09 14.1828 20.14 13.951 19.68L10.8281 13.43C10.7718 13.32 10.6806 13.23 10.5681 13.17L4.3214 10.05C3.8581 9.82 3.9062 9.14 4.3977 8.98Z");
}

</style>
