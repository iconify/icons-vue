<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zzaudlaeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:platinum-bar" /></template>
<style>
.zzaudlaeb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m22.202 18.237l-2.997-7.993l-1.747-4.992q-.019-.054-.047-.106q-.027-.051-.062-.097t-.076-.087q-.042-.04-.089-.074t-.099-.059t-.107-.044q-.055-.017-.113-.026q-.057-.009-.115-.009h-9.5q-.058 0-.115.009q-.058.009-.113.026t-.107.044q-.052.026-.099.059q-.047.034-.089.074q-.041.041-.076.087t-.062.097t-.047.106l-1.747 4.992l-2.997 7.993q-.026.069-.038.142t-.01.146q.003.074.02.146t.047.139q.031.068.074.128t.097.11t.117.089q.062.039.132.065q.127.048.263.048h19q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.136-.048-.263M17.443 9.75H6.557l1.225-3.5h8.436z");
}

</style>
