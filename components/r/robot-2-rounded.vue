<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oqrb-vbzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:robot-2-rounded" /></template>
<style>
.oqrb-vbzk {
  fill: currentColor;
  d: path("M5.808 20q-.343 0-.576-.233T5 19.193v-3.235q0-.667.475-1.139q.474-.472 1.14-.472h10.77q.666 0 1.14.475q.475.475.475 1.142v3.234q0 .343-.232.573t-.576.23zm3.48-7.423q-1.78 0-3.034-1.255T5 8.29t1.254-3.035T9.29 4h5.423q1.78 0 3.034 1.254T19 8.29t-1.254 3.034t-3.034 1.254zm.52-3.768q.211-.21.211-.52t-.21-.52t-.52-.211t-.52.21t-.211.52t.21.52t.52.211t.52-.21m5.424 0q.21-.21.21-.52t-.21-.52t-.52-.211t-.52.21t-.211.52t.21.52t.52.211t.52-.21");
}

</style>
