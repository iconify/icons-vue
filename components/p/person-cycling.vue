<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v9zos4ovo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:person-cycling" /></template>
<style>
.v9zos4ovo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.5 4q0-1.375.688-2.062q.687-.688 2.062-.688Q19 1.25 19 4t-2.75 2.75T13.5 4m-1 13.5h-2.307q-.216 1.387-1.261 2.432Q7.614 21.25 5.75 21.25t-3.182-1.318T1.25 16.75t1.318-3.182T5.75 12.25t3.182 1.318Q9.977 14.613 10.193 16h1.07l-2.428-4.653q-.029-.056-.048-.115q-.02-.06-.029-.122t-.008-.124t.013-.124t.033-.121t.053-.113t.07-.103q.04-.048.087-.089l4-3.5q.112-.099.254-.146q.141-.048.29-.038t.282.076t.232.178l.005.006l3 3.5q.098.113.144.255l.005.015l.456 1.501q.281-.033.576-.033q1.864 0 3.182 1.318t1.318 3.182t-1.318 3.182t-3.182 1.318t-3.182-1.318t-1.318-3.182q0-.267.027-.522l-.661.95q-.106.152-.269.237q-.162.084-.344.085zm.092-2.195l2.961-4.257l-2.129-2.485l-2.986 2.613zm3.641-2.607l-.017.023l.021-.01z");
}

</style>
