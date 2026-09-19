<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zv4gh3xea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="zv4gh3xea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:toilet-paper" /></template>
