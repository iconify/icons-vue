<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f43zlbc0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f43zlbc0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:text-line-spacing" /></template>
