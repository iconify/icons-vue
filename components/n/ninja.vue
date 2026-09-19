<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pekzi00tw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1536};
const content = `<path class="pekzi00tw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:ninja" /></template>
