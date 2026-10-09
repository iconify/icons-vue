<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckdxm-8ru.css';
import '../../css/f/fhd5hqc9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ckdxm-8ru"/><path class="fhd5hqc9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:oven-20" /></template>
