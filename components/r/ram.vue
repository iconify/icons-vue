<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="whomyobby"/><path class="r75t67biw"/><path class="lonu7bcet"/><path class="iuqswbbjf"/><path class="se9kk3bkk"/><path class="qm49yob8v"/><circle class="vz9doybfw"/><path class="yv-q7obsh"/><path class="h43ecbc0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:ram" /></template>
<style>
.h43ecbc0q {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M16 13.696c3.353 2.427 5.43 6.139 3.724 11.089c-1.367 3.967-6.816 3.115-9.616 1.127s-2.643-4.792-1.733-6.291c.909-1.497 4.158-1.229 6.024.097c.934.663.287 1.559-.721 1.068c-2.292-1.118-3.037 1.443-1.246 2.882c1.266 1.016 3.275 1.049 3.655-1.01c.671-3.63-3.505-6.274-7.465-5.302C11 16 13.161 11.641 16 13.696");
}

.iuqswbbjf {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M17 36c-2.75 0-4-6-4-6c0-1.104 2.646-2 3.75-2S20 27.896 20 29c0 0-.25 7-3 7");
}

.lonu7bcet {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M14 35c-2.75 0-4-6-4-6c0-1.104 2.646-2 3.75-2S17 26.896 17 28c0 0-.25 7-3 7");
}

.qm49yob8v {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M17 17.667C17 27 12.345 29 8.042 29C3.738 29 1 22.36 1 17.667S3.738 12 8.042 12c4.303 0 8.958.973 8.958 5.667");
}

.r75t67biw {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M28 36c-2.75 0-2-6-2-6c0-1.104 2.646-2 3.75-2S33 27.896 33 29c0 0-2.25 7-5 7");
}

.se9kk3bkk {
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  d: path("M35.75 21.384c0 7.782-4.495 11.408-14.519 11.408c-10.023 0-13.481-3.626-13.481-11.408c0-7.783 3.458-11.407 13.481-11.407S35.75 13.601 35.75 21.384");
}

.vz9doybfw {
  cx: 4.5px;
  cy: 20.5px;
  r: 1.5px;
  fill: var(--svg-color--292f33, #292f33);
}

.whomyobby {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M25 35c-2.75 0-2-6-2-6c0-1.104 2.646-2 3.75-2S30 26.896 30 28c0 0-2.25 7-5 7");
}

.yv-q7obsh {
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  d: path("M15.75 12.75C14 16 13.622 15.356 8.622 17.356C5.545 18.587 0 18.25 0 13.5C0 11.567 3.687 11 7 11s10.409-1.332 8.75 1.75");
}

</style>
