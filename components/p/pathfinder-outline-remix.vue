<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/seq8pl07q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="seq8pl07q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:pathfinder-outline-remix" /></template>
