<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_esyobkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="q_esyobkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:recycle-bin-throw-1-remix" /></template>
