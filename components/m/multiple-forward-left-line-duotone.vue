<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wx3w54b6k"/><path class="gj2jcwcoe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:multiple-forward-left-line-duotone" /></template>
<style>
.gj2jcwcoe {
  d: path("M8.46154 4.5L3.24533 9.34362C2.45122 10.081 2 11.1158 2 12.1994C2 13.3418 2.50122 14.4266 3.37112 15.1671L8.46154 19.5");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wx3w54b6k {
  stroke-linejoin: round;
  d: path("M7.36369 9.01041L11.336 5.47949C12.052 4.84303 12.41 4.5248 12.7052 4.65735C13.0003 4.78991 13.0003 5.2689 13.0003 6.2269V8.57148C16.667 8.57148 22.0003 10.8572 22.0003 20.0001C20.5003 17.1429 16.6003 15.4286 13.0003 15.4286V17.7732C13.0003 18.7312 13.0003 19.2102 12.7052 19.3427C12.41 19.4753 12.052 19.1571 11.336 18.5206L7.36369 14.9897C5.79506 13.5954 5.01074 12.8982 5.01074 12.0001C5.01074 11.1019 5.79506 10.4047 7.36369 9.01041Z");
}

</style>
