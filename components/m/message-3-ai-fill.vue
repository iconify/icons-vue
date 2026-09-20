<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3ji-5l8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3ji-5l8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:message-3-ai-fill" /></template>
