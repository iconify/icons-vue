<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti64bp60p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ti64bp60p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:refrigerator-remix" /></template>
