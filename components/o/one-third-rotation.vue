<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3g6p4btc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y3g6p4btc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:one-third-rotation" /></template>
