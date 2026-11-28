<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jc_k_y0gh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jc_k_y0gh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:virus-x" /></template>
