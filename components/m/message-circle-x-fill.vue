<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ir1mvbvgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ir1mvbvgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:message-circle-x-fill" /></template>
