<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o60-cbbnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:room-service-tray" /></template>
<style>
.o60-cbbnr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.5 6.25q0-2.5 2.5-2.5q1.036 0 1.768.732T14.5 6.25q0 .688-.323 1.242q2.458.565 4.363 2.469q2.44 2.439 2.683 5.789h.277q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .177-.079.335l-1.5 3q-.047.094-.117.171t-.16.132q-.089.055-.189.083q-.101.029-.205.029H4q-.104 0-.205-.029q-.1-.028-.189-.083t-.16-.132t-.117-.171l-1.5-3q-.067-.133-.077-.282q-.011-.149.036-.29q.048-.142.145-.254q.098-.113.232-.18q.158-.079.335-.079h.277Q3.02 12.4 5.46 9.961q1.865-1.864 4.261-2.445Q9.5 6.994 9.5 6.25m10.218 9.5H4.282q.239-2.729 2.239-4.728Q8.791 8.753 12 8.753t5.479 2.269q2 1.999 2.239 4.728");
}

</style>
