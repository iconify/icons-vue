<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yve2u8pfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yve2u8pfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:stox" /></template>
