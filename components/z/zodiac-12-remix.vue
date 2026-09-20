<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgep_90_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vgep_90_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:zodiac-12-remix" /></template>
