<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9incsb6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i9incsb6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:ruler-horizontal" /></template>
