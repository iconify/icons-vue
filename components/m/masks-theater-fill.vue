<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-spbpbpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:masks-theater-fill" /></template>
<style>
.f-spbpbpa {
  fill: currentColor;
  d: path("M9.223 6.918a3 3 0 0 1 2.433-3.476l5.909-1.041a3 3 0 0 1 3.476 2.433l.868 4.924a6.001 6.001 0 0 1-11.818 2.084Zm8.052-1.405a1 1 0 0 0 0 2h.01a1 1 0 1 0 0-2Zm-3.939.695a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm-11.245 8.75l.868-4.924a3 3 0 0 1 3.476-2.433l1.264.223a.999.999 0 1 1-.347 1.969L6.087 9.57a1 1 0 0 0-1.158.811l-.868 4.924a3.999 3.999 0 0 0 6.87 3.418c.302-.323.547-.695.726-1.1a1 1 0 1 1 1.829.81a6 6 0 0 1-11.395-3.475m13.097-5.01a1.26 1.26 0 0 1-.544-.402a1 1 0 0 0-1.574 1.233a3.265 3.265 0 0 0 4.713.452a3.2 3.2 0 0 0 .964-1.453a1.001 1.001 0 0 0-1.902-.62a1.27 1.27 0 0 1-1.657.79m-8.453.765a1 1 0 0 1 0 2h-.01a1 1 0 1 1 0-2ZM6.646 14a3.27 3.27 0 0 1 3.31.584c.45.386.783.889.964 1.453a.997.997 0 0 1-.64 1.261a1 1 0 0 1-1.261-.64a1.267 1.267 0 0 0-2.201-.389a1.002 1.002 0 0 1-1.659-.125a1 1 0 0 1 .084-1.108A3.2 3.2 0 0 1 6.646 14");
}

</style>
