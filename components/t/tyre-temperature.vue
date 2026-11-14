<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r17n9uy8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:tyre-temperature" /></template>
<style>
.r17n9uy8g {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.25 10.5q0-3.831 2.709-6.541Q6.669 1.25 10.5 1.25t6.541 2.709q2.709 2.71 2.709 6.541q0 .587-.064 1.148q-.519-.148-1.186-.148q-3 0-3 3v2.561q-.664.729-.896 1.759q-1.859.93-4.104.93q-3.831 0-6.541-2.709Q1.25 14.331 1.25 10.5m7 0q0-2.25 2.25-2.25t2.25 2.25t-2.25 2.25t-2.25-2.25m7.542 8.755q.182-1.033.958-1.65V14.5q0-1.75 1.75-1.75t1.75 1.75v3.105q.776.617.958 1.65q.223 1.262-.601 2.245q-.825.982-2.107.982t-2.107-.982q-.824-.983-.601-2.245M18.25 18q0 .099-.026.194t-.074.181q-.05.086-.12.155q-.069.07-.155.12q-.505.291-.606.865t.273 1.021t.958.446q.583 0 .958-.446q.374-.447.273-1.021t-.606-.865q-.086-.05-.155-.12q-.07-.069-.12-.155t-.074-.181q-.026-.095-.026-.194v-3.5q0-.25-.25-.25t-.25.25z");
}

</style>
