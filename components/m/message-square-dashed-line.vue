<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbeg3bu9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bbeg3bu9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:message-square-dashed-line" /></template>
