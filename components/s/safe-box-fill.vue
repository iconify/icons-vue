<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oy_hdcb7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oy_hdcb7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:safe-box-fill" /></template>
