<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="wkqj20_bu"/><path class="ii0j32x1e"/><g class="gs1vcob0z"><path class="glfttp97z"/><path class="aari73zjk"/><circle class="g8dcrfb-a"/><circle class="qdo_kwbvp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:mushroom" /></template>
<style>
.aari73zjk {
  d: path("M7.708 4.25c3.331 0 6.041 2.71 6.041 6.042s-2.71 6.042-6.041 6.042a6.014 6.014 0 0 1-6.006-5.394a17.8 17.8 0 0 1 4.931-6.59c.364-.067.726-.1 1.075-.1m0-.25c-.405 0-.8.042-1.184.115A17.96 17.96 0 0 0 1.448 10.9A6.291 6.291 0 1 0 7.708 4M26 9.5a4.497 4.497 0 0 0 8.666 1.689l-.001-.002a17.9 17.9 0 0 0-4.208-6.182A4.496 4.496 0 0 0 26 9.5");
}

.g8dcrfb-a {
  cx: 21.5px;
  cy: 16px;
  r: 4.5px;
}

.glfttp97z {
  d: path("M7.708 16.583A6.292 6.292 0 1 0 7.708 4c-.405 0-.8.042-1.184.115A17.96 17.96 0 0 0 1.448 10.9a6.29 6.29 0 0 0 6.26 5.683");
}

.gs1vcob0z {
  fill: var(--svg-color--f4abba, #f4abba);
}

.ii0j32x1e {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("m34.666 11.189l-.001-.002a17.9 17.9 0 0 0-4.208-6.182h-.003A17.92 17.92 0 0 0 18 0A17.96 17.96 0 0 0 0 18a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4c0-2.417-.48-4.713-1.334-6.811");
}

.qdo_kwbvp {
  cx: 20px;
  cy: 5px;
  r: 3px;
}

.wkqj20_bu {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M27 33c0 2.209-1.791 3-4 3H13c-2.209 0-4-.791-4-3s3-7 3-13s12-6 12 0s3 10.791 3 13");
}

</style>
