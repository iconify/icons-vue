<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ey3ko8bcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ey3ko8bcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:webhook-duotone-round" /></template>
