<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aub2nm7hz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="aub2nm7hz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:music-note-2-solid" /></template>
