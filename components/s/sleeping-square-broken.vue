<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="glsnqibje"/><path class="b6ykzlr9k"/><path class="y4d_v7b6v"/><path class="yod4tl2uo"/><path class="hxs31xblj"/><path class="pr1jznbmm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sleeping-square-broken" /></template>
<style>
.b6ykzlr9k {
  d: path("M13.5 11C14.0669 11.6303 14.7564 12 15.5 12C16.2436 12 16.9331 11.6303 17.5 11");
}

.glsnqibje {
  d: path("M6.5 11C7.06692 11.6303 7.75638 12 8.5 12C9.24362 12 9.93308 11.6303 10.5 11");
}

.hxs31xblj {
  stroke-linejoin: round;
  d: path("M14.0479 5.49988L15.7799 6.49988L13.0479 7.23193L14.7799 8.23193");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pr1jznbmm {
  stroke-linejoin: round;
  d: path("M12 16H12.0001");
}

.y4d_v7b6v {
  d: path("M22 12C22 16.714 22 19.0711 20.5355 20.5355C19.0711 22 16.714 22 12 22C7.28595 22 4.92893 22 3.46447 20.5355C2.49073 19.5618 2.16444 18.1934 2.0551 16M12 2C7.28595 2 4.92893 2 3.46447 3.46447C2 4.92893 2 7.28595 2 12");
}

.yod4tl2uo {
  stroke-linejoin: round;
  d: path("M17 4L20.4641 2L19 7.4641L22.4641 5.4641");
}

</style>
