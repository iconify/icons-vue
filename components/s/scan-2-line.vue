<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyapg9piq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xyapg9piq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:scan-2-line" /></template>
