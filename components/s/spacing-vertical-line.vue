<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sg_p2w5ra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sg_p2w5ra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:spacing-vertical-line" /></template>
