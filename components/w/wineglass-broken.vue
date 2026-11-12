<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="a4vliqeko"/><path class="gijxu7_gu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wineglass-broken" /></template>
<style>
.a4vliqeko {
  d: path("M12 15.2856V20.9999M12 20.9999H15.75M12 20.9999H8.25M8 3H6.89474C5.8483 3 5 3.8483 5 4.89474V8C5 11.866 8.13401 15 12 15C15.866 15 19 11.866 19 8V4.89474C19 3.8483 18.1517 3 17.1053 3H12");
}

.gijxu7_gu {
  d: path("M5.5 8.99997C5.5 8.99997 7.58115 8.08724 9 7.99997C10.2326 7.92416 11.1163 8.46207 12 8.99997M18.5 8.99997C18.5 8.99997 16.4188 9.91271 15 9.99997");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
