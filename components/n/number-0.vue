<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0bxq3day.css';
import '../../css/e/e3t8n_b1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r0bxq3day"/><path class="e3t8n_b1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:number-0" /></template>
