<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_n-dbbym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_n-dbbym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mingcute-line" /></template>
