<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qq1kgtqzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="qq1kgtqzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:martini-glass-empty" /></template>
