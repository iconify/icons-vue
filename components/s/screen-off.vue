<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zr396pfqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zr396pfqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:screen-off" /></template>
