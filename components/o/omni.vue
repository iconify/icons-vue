<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqzea8bce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xqzea8bce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:omni" /></template>
