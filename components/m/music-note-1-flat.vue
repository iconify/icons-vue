<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5xhfbbdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u5xhfbbdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:music-note-1-flat" /></template>
