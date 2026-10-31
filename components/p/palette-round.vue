<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngxjcr4ra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ngxjcr4ra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:palette-round" /></template>
