<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1jix6p0z.css';
import '../../css/x/xw4xmi69j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="i1jix6p0z"/><path class="xw4xmi69j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:mobile-4" /></template>
