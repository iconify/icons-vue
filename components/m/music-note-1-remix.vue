<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6d1w-b2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="q6d1w-b2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:music-note-1-remix" /></template>
