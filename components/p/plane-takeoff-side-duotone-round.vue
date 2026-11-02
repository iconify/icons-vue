<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="b--0-wb7z"/><path class="ma5votvlf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plane-takeoff-side-duotone-round" /></template>
<style>
.b--0-wb7z {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m6.764 12l.894-.447l-2.052-4.106a2.1 2.1 0 0 1-.115-1.617c.363-1.09 1.504-1.64 2.611-1.461a2.55 2.55 0 0 1 1.396.714l3.699 3.7L18.764 6A2.234 2.234 0 0 1 22 8v.764a3 3 0 0 1-1.658 2.683L7.87 17.683c-.417.21-.876.318-1.342.317H6c-.992 0-1.898-.56-2.342-1.447l-.552-1.106A2.38 2.38 0 0 1 5.236 12Z");
}

.ft5dv1b6b {
  fill: none;
}

.ma5votvlf {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m7 13l2-1l-2.5-5A1.12 1.12 0 0 1 7 5.5a1.55 1.55 0 0 1 1.79.29L13 10l6.211-3.106A1.236 1.236 0 0 1 21 8v.764a2 2 0 0 1-1.106 1.789L7.422 16.789a2 2 0 0 1-.894.211H6a1.62 1.62 0 0 1-1.447-.894L4 15c-.46-.919.209-2 1.236-2zm-4 8h18");
}

</style>
