<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqu14h6hf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zqu14h6hf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:pacman-solid" /></template>
