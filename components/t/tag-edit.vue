<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njg7ipjzz.css';
import '../../css/s/sodj30gif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="njg7ipjzz"/><path class="sodj30gif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:tag-edit" /></template>
