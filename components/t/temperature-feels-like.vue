<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyt_auroj.css';
import '../../css/y/ymie1nvqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dyt_auroj"/><path class="ymie1nvqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:temperature-feels-like" /></template>
