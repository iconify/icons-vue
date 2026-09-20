<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cz4uhub5s.css';
import '../../css/l/l8wwf1bsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cz4uhub5s"/><path class="l8wwf1bsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:mcp-24" /></template>
