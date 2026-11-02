<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvkdr3wzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rvkdr3wzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:strikethrough-fill" /></template>
