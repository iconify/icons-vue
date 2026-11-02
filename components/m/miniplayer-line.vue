<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dszx4tb5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dszx4tb5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:miniplayer-line" /></template>
