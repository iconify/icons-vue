<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqreqvbhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tqreqvbhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:store-factory-remix" /></template>
