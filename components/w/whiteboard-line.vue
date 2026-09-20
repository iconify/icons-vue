<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfvpunchv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfvpunchv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:whiteboard-line" /></template>
