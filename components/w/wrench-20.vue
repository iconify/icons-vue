<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mt_i27b9p.css';
import '../../css/s/s60hnq-cg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mt_i27b9p"/><path class="s60hnq-cg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wrench-20" /></template>
