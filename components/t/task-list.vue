<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-bko7bcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="u-bko7bcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:task-list" /></template>
