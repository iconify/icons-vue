<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h411zk6qf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:packages-fill-sharp" /></template>
<style>
.h411zk6qf {
  fill: currentColor;
  d: path("M16.947 4.356a1 1 0 0 1 .553.894v5.007l3.947 1.974a1 1 0 0 1 .553.894v5.625a1 1 0 0 1-.553.894l-4.5 2.25a1 1 0 0 1-.894 0L12 19.868l-4.053 2.026a1 1 0 0 1-.894 0l-4.5-2.25A1 1 0 0 1 2 18.75v-5.625c0-.379.214-.725.553-.894L6.5 10.257V5.25c0-.379.214-.725.553-.894l4.5-2.25a1 1 0 0 1 .894 0ZM12 6.382l2.264-1.132L12 4.118L9.736 5.25Zm1 1.736v3.389l2.5-1.25V6.868Zm-5.5 6.139l2.264-1.132L7.5 11.993l-2.264 1.132Zm6.736-1.132l2.264 1.132l2.264-1.132l-2.264-1.132ZM11 14.743l-2.5 1.25v3.389l2.5-1.25Zm6.5 1.25v3.389l2.5-1.25v-3.389Z");
}

</style>
