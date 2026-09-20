<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucluwrb2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ucluwrb2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pixel-arrow-top-left" /></template>
