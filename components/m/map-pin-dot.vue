<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="stwiewb7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:map-pin-dot" /></template>
<style>
.stwiewb7e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.498 17.557q-.514-.462-1.708-1.416Q4.75 12.118 4.75 9q0-3.003 2.123-5.127T12 1.75t5.127 2.123Q19.25 5.997 19.25 9q0 3.118-5.04 7.141q-1.194.954-1.708 1.416q-.051.047-.11.083t-.123.06t-.132.037t-.137.013t-.137-.013q-.067-.012-.132-.037q-.064-.024-.123-.06t-.11-.083M12 5.75Q8.75 5.75 8.75 9T12 12.25T15.25 9T12 5.75M10.25 21q0-1.75 1.75-1.75T13.75 21T12 22.75T10.25 21");
}

</style>
