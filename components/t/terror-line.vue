<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mf2faab1e.css';
import '../../css/d/d3yssn4fe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mf2faab1e"/><path class="d3yssn4fe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:terror-line" /></template>
