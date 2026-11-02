<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ks1b49xoq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ks1b49xoq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:spotify-line" /></template>
