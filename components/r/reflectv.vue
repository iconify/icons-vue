<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zuw0fpp4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zuw0fpp4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:reflectv" /></template>
