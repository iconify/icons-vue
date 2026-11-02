<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvu3bccsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xvu3bccsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mosaic-fill" /></template>
