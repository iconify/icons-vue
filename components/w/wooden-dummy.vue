<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ezz7qqbxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:wooden-dummy" /></template>
<style>
.ezz7qqbxy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.25 11.929V8.174q.337.076.75.076h3q2.25 0 2.25-2.25T19 3.75h-3q-.49 0-.873.107Q14.617 1.75 12 1.75Q8.75 1.75 8.75 5v6.929l-4.494-1.634q-.14-.051-.289-.044t-.284.069t-.236.173t-.152.251q-.025.069-.036.142q-.012.073-.008.147q.003.074.021.145q.017.072.048.139q.032.067.075.127q.044.059.098.109t.118.088q.063.039.133.064l5.006 1.82V19q0 1.346.952 2.298T12 22.25t2.298-.952T15.25 19v-5.475l5.006-1.82q.07-.025.133-.064q.063-.038.118-.088t.098-.109t.075-.127q.031-.067.048-.139q.018-.071.021-.145t-.008-.147t-.036-.142t-.064-.133t-.088-.118t-.109-.098t-.127-.075t-.139-.048t-.145-.021t-.147.008t-.142.036z");
}

</style>
