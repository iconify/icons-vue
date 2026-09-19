<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sj3dylsqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1664};
const content = `<path class="sj3dylsqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:window" /></template>
