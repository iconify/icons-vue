<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="em0cihb0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:survivor" /></template>
<style>
.em0cihb0g {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m8.849 11.128l2.287-4.003l-1.279-2.239q-.8-1.334.049-2.437Q10.636 1.5 12 1.5t2.094.949q.849 1.103.057 2.423l-1.287 2.253l2.287 4.003l.001.002q.577.363 1.091.877Q18 13.765 18 16.25t-1.757 4.243T12 22.25t-4.243-1.757Q6 18.735 6 16.25t1.757-4.243q.514-.514 1.091-.877zm4-7q.282-.471.057-.764Q12.626 3 12 3t-.906.364q-.225.293.049.75L12 5.613zm-1.811 6.192q.467-.07.962-.07t.962.07L12 8.637zm2.022 3.649q-.382-.559-1.06-.559t-1.06.559l-.139.203q-.15.22-.406.296l-.237.07q-.649.191-.858.835t.202 1.178l.152.198q.163.211.155.477l-.007.246q-.019.677.529 1.075t1.184.171l.233-.082q.252-.09.505 0l.23.082q.638.227 1.186-.171t.529-1.075l-.007-.245q-.008-.267.157-.48l.148-.194q.413-.537.204-1.18q-.209-.644-.858-.835l-.237-.07q-.256-.076-.406-.296l-.139-.202z");
}

</style>
