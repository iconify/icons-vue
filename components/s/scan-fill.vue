<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsu69y5bp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xsu69y5bp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:scan-fill" /></template>
