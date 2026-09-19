<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_nh06b7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p_nh06b7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:paint-brush" /></template>
