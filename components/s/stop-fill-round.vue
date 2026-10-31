<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lr-vo4brq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lr-vo4brq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:stop-fill-round" /></template>
