<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ou-0c4bbm"/><path class="gtg72fbwi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:treasury-payroll-run" /></template>
<style>
.gtg72fbwi {
  d: path("m15 14.5l6.5 3.5l-6.5 3.5Z");
}

.ou-0c4bbm {
  d: path("M12.2 21.5H4.5v-19h15v11.2M8 6.5h3.5M8 10h4.2m.3 0H16m-8 3.5h4.2M8 17h2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
