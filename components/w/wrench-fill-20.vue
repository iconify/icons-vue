<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ry-l2ebjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ry-l2ebjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:wrench-fill-20" /></template>
