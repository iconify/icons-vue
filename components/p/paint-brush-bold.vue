<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgx6o05ak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="zgx6o05ak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:paint-brush-bold" /></template>
