<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ih_hx3b5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ih_hx3b5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:scanner-1-remix" /></template>
