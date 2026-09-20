<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-fw0acxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-fw0acxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pencil-3-ai-line" /></template>
