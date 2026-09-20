<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":431};
const content = `<path class="yiya5rbyk"/><path class="mmwxkhu0z"/><path class="wf7czlpnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:section-icon" /></template>
<style>
.mmwxkhu0z {
  fill: var(--svg-color--00a86b, #00a86b);
  d: path("M179.319 0L0 65.041v300.15l179.319 65.052zM31.954 347.564V82.69l111.557-34.431v333.725l-111.557-34.43z");
}

.wf7czlpnc {
  fill: var(--svg-color--038754, #038754);
  d: path("m179.319 109.88l17.693-3.744V69.973l-17.693 4.742zm0 245.437l17.693 4.776v-36.197l-17.693-3.777z");
}

.yiya5rbyk {
  fill: var(--svg-color--00a86b, #00a86b);
  d: path("m98.184 302.837l121.62 25.912V101.305l-121.62 25.812zm157.827 73.216L69.03 325.517V104.36l186.703-50.17l.267 321.874z");
}

</style>
