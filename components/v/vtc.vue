<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcs0dxbfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lcs0dxbfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:vtc" /></template>
