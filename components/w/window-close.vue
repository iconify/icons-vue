<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6h-p980a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1536};
const content = `<path class="p6h-p980a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:window-close" /></template>
