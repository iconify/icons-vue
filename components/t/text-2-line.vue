<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mctny38gj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mctny38gj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:text-2-line" /></template>
