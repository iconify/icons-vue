<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zovnqnbdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:white-blood-cell" /></template>
<style>
.zovnqnbdt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.969 1.75q-3.423.01-6.399 2.136Q1.75 6.56 1.75 12q0 4.46 4.54 8.092q3.997 3.109 8.892 1.886q.028-.007.055-.016q5.163-1.722 6.487-7.015q1.267-4.646-1.845-9.106q-2.719-4.509-7.91-4.091m-4.33 11.722Q6.25 12.413 6.25 10.75q0-2.443 2.443-3.435q2.107-1.04 3.518.235q.77-.721 2.042-.768q1.945-.072 2.898 1.596q.92 1.61.07 3.169q-.516.946-1.376 1.381q.372 1.028-.037 2.302q-.655 2.035-2.725 2.265q-1.887.236-2.885-1.19q-.641-.915-.586-2.036q-1.064-.105-1.973-.797");
}

</style>
