<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/is_njbszx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="is_njbszx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:music-note-circle-solid" /></template>
