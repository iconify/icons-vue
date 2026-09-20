<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfzld3bmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="yfzld3bmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:night-lightning" /></template>
