<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vs_grrb1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vs_grrb1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:phone-duocolor-round" /></template>
