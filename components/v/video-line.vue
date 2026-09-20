<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/us-21_hyf.css';
import '../../css/p/p-8ny1bzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="us-21_hyf"/><path class="p-8ny1bzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:video-line" /></template>
