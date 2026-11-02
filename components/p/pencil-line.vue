<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h0lhy16hc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h0lhy16hc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pencil-line" /></template>
