<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywx6ye69t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="ywx6ye69t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:windy" /></template>
