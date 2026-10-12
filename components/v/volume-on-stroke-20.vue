<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yyz7sxb6l.css';
import '../../css/z/zhwfo4bgb.css';
import '../../css/n/ngnbw93bi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yyz7sxb6l"/><path class="zhwfo4bgb"/><path class="ngnbw93bi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:volume-on-stroke-20" /></template>
