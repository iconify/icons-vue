<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgfy970-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wgfy970-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:table-add" /></template>
