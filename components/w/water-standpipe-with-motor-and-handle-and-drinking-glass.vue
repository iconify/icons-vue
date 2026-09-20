<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7jobn3po.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="v7jobn3po"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:water-standpipe-with-motor-and-handle-and-drinking-glass" /></template>
