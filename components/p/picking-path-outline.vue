<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvbbt4bak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wvbbt4bak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:picking-path-outline" /></template>
