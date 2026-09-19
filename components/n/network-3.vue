<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knsyygmgu.css';
import '../../css/a/a6hum9hrz.css';
import '../../css/d/doyyo9bqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="knsyygmgu"/><path class="a6hum9hrz"/><path class="doyyo9bqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:network-3" /></template>
