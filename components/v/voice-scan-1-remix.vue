<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5tdrabfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e5tdrabfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:voice-scan-1-remix" /></template>
