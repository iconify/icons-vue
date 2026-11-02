<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtk_gfbzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dtk_gfbzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:message-square-warning-fill" /></template>
