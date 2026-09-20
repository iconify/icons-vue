<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="vxa48us6c"/><g class="cozpm7b9z"><path class="klcunpygg"/><path class="b_m0eu2ns"/><path class="zlfn5wdzo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:shorts" /></template>
<style>
.b_m0eu2ns {
  d: path("m32.583 13.914l-.421-2.107c-2.41-.408-6.491-1.701-7.87-5.807h-2.074c1.464 5.511 6.759 7.506 10.365 7.914M17 6v21.091l1-2.636l1 2.636V6z");
}

.cozpm7b9z {
  fill: var(--svg-color--5d9040, #5d9040);
}

.klcunpygg {
  d: path("M5 4h26v2H5zm8.782 2h-2.074c-1.378 4.107-5.46 5.399-7.87 5.807l-.421 2.107c3.606-.408 8.9-2.403 10.365-7.914");
}

.vxa48us6c {
  fill: var(--svg-color--78b159, #78b159);
  d: path("M31 6V1.955A.956.956 0 0 0 30.045 1H5.955A.956.956 0 0 0 5 1.955V6L0 31l14 4l4-10.545L22 35l14-4z");
}

.zlfn5wdzo {
  d: path("M18.149 23H18v-2h.149A2.853 2.853 0 0 0 21 18.149V5h2v13.149A4.856 4.856 0 0 1 18.149 23");
}

</style>
