<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ow0w91b8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ow0w91b8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:music-note-trebble-clef" /></template>
