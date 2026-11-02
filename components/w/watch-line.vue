<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgz6ohbir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qgz6ohbir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:watch-line" /></template>
