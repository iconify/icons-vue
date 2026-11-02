<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yuxv95x_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yuxv95x_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:toxophily-line" /></template>
