<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xu7rcfbcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xu7rcfbcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:wave-hand-line" /></template>
