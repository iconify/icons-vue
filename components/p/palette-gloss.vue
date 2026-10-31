<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-pi8n4vl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-pi8n4vl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:palette-gloss" /></template>
