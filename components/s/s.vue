<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-8x2bf4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g-8x2bf4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:s" /></template>
