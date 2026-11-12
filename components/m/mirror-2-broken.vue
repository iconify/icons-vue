<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="n9m6iabsi"/><path class="sjrvvrbqw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:mirror-2-broken" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n9m6iabsi {
  d: path("M21 12.168C21 7.10468 16.9706 3 12 3C7.02944 3 3 7.10468 3 12.168C3 13.9413 3.49422 15.597 4.35 17");
}

.sjrvvrbqw {
  d: path("M18.3636 22H5.63636C3.62806 22 2 20.3719 2 18.3636C2 17.6105 2.61052 17 3.36364 17H7.17157C7.70201 17 8.21071 17.2107 8.58579 17.5858L9.41421 18.4142C9.78929 18.7893 10.298 19 10.8284 19H13.1716C13.702 19 14.2107 18.7893 14.5858 18.4142L15.4142 17.5858C15.7893 17.2107 16.298 17 16.8284 17H20.6364C21.3895 17 22 17.6105 22 18.3636C22 20.3719 20.3719 22 18.3636 22Z");
}

</style>
