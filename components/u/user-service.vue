<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyrdkflpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fyrdkflpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:user-service" /></template>
