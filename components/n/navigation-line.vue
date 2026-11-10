<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c06cgmbtm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:navigation-line" /></template>
<style>
.c06cgmbtm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 6.001V2.0016M6.051 21.3285L11.5882 10.2503C11.7579 9.9203 12.2421 9.9203 12.4118 10.2503L17.9489 21.3285C18.1325 21.6984 17.7807 22.0983 17.3916 21.9784L12.1456 20.2286C12.0511 20.1887 11.9489 20.1887 11.8544 20.2286L6.6085 21.9784C6.2193 22.0983 5.8676 21.6984 6.051 21.3285Z");
}

</style>
