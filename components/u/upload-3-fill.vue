<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxvt099fo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vxvt099fo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:upload-3-fill" /></template>
