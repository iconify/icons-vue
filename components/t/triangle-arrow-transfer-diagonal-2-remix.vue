<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ia5zytlyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ia5zytlyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:triangle-arrow-transfer-diagonal-2-remix" /></template>
