<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vk-_l-3je.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vk-_l-3je"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:pen-tool-remix" /></template>
