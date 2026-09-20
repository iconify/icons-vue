<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bt0ai8dma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bt0ai8dma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sim-card-outline" /></template>
