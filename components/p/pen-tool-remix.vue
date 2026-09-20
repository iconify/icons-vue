<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwrtx0vnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lwrtx0vnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:pen-tool-remix" /></template>
