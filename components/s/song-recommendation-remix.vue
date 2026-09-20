<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nw5orqblc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="nw5orqblc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:song-recommendation-remix" /></template>
