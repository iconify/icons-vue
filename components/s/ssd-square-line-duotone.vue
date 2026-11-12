<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="zkb-edy8n"/><path class="u3qsncrba"/><path class="zqtjw2ejn"/><path class="x9lvmbcxu"/><path class="uqqo67wig"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ssd-square-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u3qsncrba {
  d: path("M16.5 17V18");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.uqqo67wig {
  d: path("M21.8515 14.9557L19 5.11765C18.5 3.52941 17.6046 3 16.5 3H7.5C6.39543 3 5.5 3.52941 5 5.11765L2.14849 14.9557M2 17.2941C2 15.807 2 15.0635 2.33706 14.5294C2.48298 14.2982 2.67048 14.0996 2.88886 13.9451C3.39331 13.5882 4.09554 13.5882 5.5 13.5882H18.5C19.9045 13.5882 20.6067 13.5882 21.1111 13.9451C21.3295 14.0996 21.517 14.2982 21.6629 14.5294C22 15.0635 22 15.807 22 17.2941C22 18.7812 22 19.5247 21.6629 20.0589C21.517 20.2901 21.3295 20.4886 21.1111 20.6431C20.6067 21 19.9045 21 18.5 21H5.5C4.09554 21 3.39331 21 2.88886 20.6431C2.67048 20.4886 2.48298 20.2901 2.33706 20.0589C2 19.5247 2 18.7812 2 17.2941Z");
}

.x9lvmbcxu {
  d: path("M11.5 17V18");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.zkb-edy8n {
  d: path("M19 17V18");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.zqtjw2ejn {
  d: path("M14 17V18");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
