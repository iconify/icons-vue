<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="axa1bjb4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:potted-plant" /></template>
<style>
.axa1bjb4u {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.75 13.75V9.727q2.833-.18 4.727-1.742Q19.75 6.11 19.75 3q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T19 2.25q-3.338 0-5.477 1.765q-1.102.909-1.67 2.109Q10.113 2.75 5 2.75q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146q0 7.365 7 7.731v2.519H7.741q-1.22.001-1.97.962t-.455 2.144l.875 3.5q.473 1.893 2.425 1.894h6.768q1.952-.001 2.425-1.894l.875-3.5q.295-1.183-.455-2.144t-1.97-.962z");
}

</style>
