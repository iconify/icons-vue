<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kt25ylb-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kt25ylb-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:radiation-round" /></template>
