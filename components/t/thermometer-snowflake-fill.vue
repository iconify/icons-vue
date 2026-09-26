<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="icw8xf3sp"/><path class="zxf7jobax"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:thermometer-snowflake-fill" /></template>
<style>
.icw8xf3sp {
  fill: currentColor;
  d: path("M13.5 5C13.5 2.7909 15.2909 1 17.5 1C19.7091 1 21.5 2.7909 21.5 5L21.5 13.7251C22.4634 14.7459 23 16.0964 23 17.5C23 20.5376 20.5376 23 17.5 23C14.4624 23 12 20.5376 12 17.5C12 16.0964 12.5366 14.7459 13.5 13.7251L13.5 5ZM18.5 14.1459L18.5 5C18.5 4.4477 18.0523 4 17.5 4C16.9477 4 16.5 4.4477 16.5 5L16.5 14.1459C15.0167 14.5881 14 15.9522 14 17.5C14 19.433 15.567 21 17.5 21C19.433 21 21 19.433 21 17.5C21 15.9522 19.9833 14.5881 18.5 14.1459ZM19 17.5C19 18.3284 18.3284 19 17.5 19C16.6716 19 16 18.3284 16 17.5C16 16.6716 16.6716 16 17.5 16C18.3284 16 19 16.6716 19 17.5Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zxf7jobax {
  d: path("M9.7809 10.7545L6.4148 16.5848M7.0619 18.9996L6.4148 16.5848L4 17.2319M10.5 12L3.7678 12M2 13.7678L3.7678 12L2 10.2322M9.7809 13.2455L6.4148 7.4152M4 6.7681L6.4148 7.4152L7.0619 5.0004");
}

</style>
