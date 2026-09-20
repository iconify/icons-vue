<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vub338lzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vub338lzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:ordered-list" /></template>
