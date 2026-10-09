<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltqeu13ri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ltqeu13ri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:smr-20-bold" /></template>
