<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyn_k2bhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dyn_k2bhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pause-20-bold" /></template>
