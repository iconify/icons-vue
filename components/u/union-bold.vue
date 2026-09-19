<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ym02-6qjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ym02-6qjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:union-bold" /></template>
