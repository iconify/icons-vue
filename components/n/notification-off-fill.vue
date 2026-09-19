<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vexlxfb7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vexlxfb7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:notification-off-fill" /></template>
