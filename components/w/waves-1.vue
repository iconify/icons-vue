<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwwq-4bef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="dwwq-4bef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:waves-1" /></template>
