<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ep6igybrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ep6igybrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:number-7" /></template>
