<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ue600zb1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ue600zb1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sparkles-3-line" /></template>
