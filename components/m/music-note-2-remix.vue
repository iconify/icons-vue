<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gb1o6dbkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gb1o6dbkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:music-note-2-remix" /></template>
