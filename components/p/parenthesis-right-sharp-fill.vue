<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q62l-w1xl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:parenthesis-right-sharp-fill" /></template>
<style>
.q62l-w1xl {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.7142 1.6897L10.0098 2C12.5776 4.6962 14.0098 8.2767 14.0098 12C14.0098 15.7233 12.5776 19.3038 10.0098 22L9.7142 22.3103");
}

</style>
