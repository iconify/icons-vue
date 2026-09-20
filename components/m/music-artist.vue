<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fs1keu_xn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fs1keu_xn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:music-artist" /></template>
