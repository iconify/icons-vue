<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqe5nibdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wqe5nibdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:star-stroke-20" /></template>
