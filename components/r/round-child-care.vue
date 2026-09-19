<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="vhr2lj4be"/><circle class="ifds6hbbc"/><path class="hr66c9but"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-child-care" /></template>
<style>
.hr66c9but {
  fill: currentColor;
  d: path("M16.1 14H7.9c-.19 0-.32.2-.23.37C8.5 15.94 10.13 17 12 17s3.5-1.06 4.33-2.63a.262.262 0 0 0-.23-.37m6.84-2.66a4.01 4.01 0 0 0-2.81-3.17a9.1 9.1 0 0 0-2.19-2.91C16.36 3.85 14.28 3 12 3s-4.36.85-5.94 2.26c-.92.81-1.67 1.8-2.19 2.91a3.99 3.99 0 0 0-2.81 3.17Q1 11.655 1 12t.06.66a4.01 4.01 0 0 0 2.81 3.17a9 9 0 0 0 2.17 2.89C7.62 20.14 9.71 21 12 21s4.38-.86 5.97-2.28c.9-.8 1.65-1.79 2.17-2.89a4 4 0 0 0 2.8-3.17q.06-.315.06-.66t-.06-.66M19 14c-.1 0-.19-.02-.29-.03c-.2.67-.49 1.29-.86 1.86C16.6 17.74 14.45 19 12 19s-4.6-1.26-5.85-3.17c-.37-.57-.66-1.19-.86-1.86c-.1.01-.19.03-.29.03c-1.1 0-2-.9-2-2s.9-2 2-2c.1 0 .19.02.29.03c.2-.67.49-1.29.86-1.86C7.4 6.26 9.55 5 12 5s4.6 1.26 5.85 3.17c.37.57.66 1.19.86 1.86c.1-.01.19-.03.29-.03c1.1 0 2 .9 2 2s-.9 2-2 2");
}

.ifds6hbbc {
  cx: 9.5px;
  cy: 10.5px;
  r: 1.25px;
  fill: currentColor;
}

.vhr2lj4be {
  cx: 14.5px;
  cy: 10.5px;
  r: 1.25px;
  fill: currentColor;
}

</style>
