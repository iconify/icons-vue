<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dash5mbrn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dash5mbrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pingpong-line" /></template>
