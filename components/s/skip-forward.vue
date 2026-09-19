<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ao8jygbgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ao8jygbgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:skip-forward" /></template>
