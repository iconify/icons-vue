<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f98zace8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="f98zace8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:point" /></template>
