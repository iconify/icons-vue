<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzzr42bvz.css';
import '../../css/i/ieg0qmbgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fzzr42bvz"/><path class="ieg0qmbgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:spray-paint" /></template>
