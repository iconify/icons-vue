<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mj5__ebsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mj5__ebsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:smiley-crying-1-remix" /></template>
