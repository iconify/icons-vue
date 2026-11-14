<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f9kte8bzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:regatta-mark" /></template>
<style>
.f9kte8bzq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.75 8q0-2.175 1.538-3.712Q9.825 2.75 12 2.75t3.712 1.538Q17.25 5.825 17.25 8t-1.538 3.712q-1.265 1.266-2.962 1.49v3.048H19q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .154-.061.295l-1.5 3.5q-.043.102-.114.186q-.07.085-.162.145q-.092.061-.197.092q-.106.032-.216.032h-11q-.11 0-.216-.032q-.105-.031-.197-.092q-.092-.06-.162-.145t-.114-.186l-1.5-3.5q-.029-.067-.045-.14q-.015-.072-.016-.146t.013-.146q.013-.073.041-.142q.027-.068.067-.13t.092-.115t.113-.094q.061-.042.129-.071q.141-.061.295-.061h6.25v-3.048q-1.697-.224-2.962-1.49Q6.75 10.175 6.75 8");
}

</style>
