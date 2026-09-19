<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k3_-rtinw"/><path class="an6yjgpdc"/><path class="gwnwx9dot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:onlyoffice-documents" /></template>
<style>
.an6yjgpdc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m13.227 19.278l-5.584 2.606a2.295 2.295 0 0 0-.001 4.16l13.995 6.54a5.74 5.74 0 0 0 4.857.002l13.863-6.47a2.295 2.295 0 0 0 .001-4.159l-5.585-2.61");
}

.gwnwx9dot {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.227 28.654L7.643 31.26a2.295 2.295 0 0 0-.001 4.16l13.995 6.54a5.74 5.74 0 0 0 4.857.001l13.863-6.47a2.295 2.295 0 0 0 .001-4.159l-5.585-2.61");
}

.k3_-rtinw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.358 12.581L26.363 6.04a5.74 5.74 0 0 0-4.857-.001l-13.863 6.47a2.295 2.295 0 0 0-.001 4.159l13.995 6.541a5.74 5.74 0 0 0 4.857.002l13.863-6.471a2.295 2.295 0 0 0 .001-4.159");
}

</style>
