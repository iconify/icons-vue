<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxuzy2bmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxuzy2bmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-minus-corner-round" /></template>
