<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xiy1i9ggn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="xiy1i9ggn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:naver-square" /></template>
