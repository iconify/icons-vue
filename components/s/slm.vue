<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hd4xszy-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hd4xszy-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:slm" /></template>
