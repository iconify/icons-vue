<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itv_042ot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="itv_042ot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:translate-2-ai-fill" /></template>
