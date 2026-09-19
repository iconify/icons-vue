<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwe3k093t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pwe3k093t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:paint-brush-alt" /></template>
