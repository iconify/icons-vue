<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5u6034ce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":512};
const content = `<path class="p5u6034ce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:ruler-vertical" /></template>
