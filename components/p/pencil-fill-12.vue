<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4_9pb1zj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="k4_9pb1zj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:pencil-fill-12" /></template>
