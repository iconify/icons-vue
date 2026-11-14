<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mqxjuruhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pills-scattered" /></template>
<style>
.mqxjuruhz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.568 3.818Q2.25 5.136 2.25 7t1.318 3.182T6.75 11.5t3.182-1.318T11.25 7T9.932 3.818T6.75 2.5T3.568 3.818M12.75 7q0-1.864 1.318-3.182T17.25 2.5t3.182 1.318T21.75 7t-1.318 3.182T17.25 11.5t-3.182-1.318T12.75 7m-5.371 6.877Q5.25 15.119 5.25 17t2.129 3.123Q9.312 21.25 12 21.25t4.621-1.127Q18.75 18.881 18.75 17t-2.129-3.123Q14.688 12.75 12 12.75t-4.621 1.127m6.251 6.31l-1.812-6.762q-.019-.071-.051-.138q-.033-.066-.078-.125t-.101-.107q-.055-.049-.119-.086t-.134-.06t-.143-.034q-.073-.009-.147-.004t-.145.024t-.138.051t-.125.078t-.107.1q-.049.056-.086.12t-.06.134t-.034.143q-.009.073-.004.147t.024.145l1.812 6.762q.019.071.051.138q.033.066.078.125t.101.107q.055.049.119.086t.134.06t.143.034q.073.009.147.004t.145-.024q.144-.038.263-.129q.118-.091.193-.22q.074-.129.094-.277q.019-.148-.02-.292");
}

</style>
