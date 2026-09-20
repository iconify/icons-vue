<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/doos-3v8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="doos-3v8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:question-2-line" /></template>
