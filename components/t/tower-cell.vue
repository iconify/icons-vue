<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgpth7i1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="wgpth7i1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:tower-cell" /></template>
