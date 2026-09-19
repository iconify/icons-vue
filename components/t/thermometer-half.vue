<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-_ea2b1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1792};
const content = `<path class="c-_ea2b1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:thermometer-half" /></template>
