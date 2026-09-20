<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/euz42-bsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="euz42-bsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:multimedia-controls-loop-arrow" /></template>
