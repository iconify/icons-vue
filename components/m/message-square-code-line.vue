<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wi1ixteyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wi1ixteyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:message-square-code-line" /></template>
