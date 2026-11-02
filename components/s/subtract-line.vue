<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ys2zd9bbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ys2zd9bbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:subtract-line" /></template>
