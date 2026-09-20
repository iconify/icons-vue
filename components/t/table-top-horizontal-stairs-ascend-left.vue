<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s83lq0lzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="s83lq0lzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:table-top-horizontal-stairs-ascend-left" /></template>
