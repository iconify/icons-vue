<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ai5qp9qio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ai5qp9qio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:volume-mute-line" /></template>
