<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gx-12vb8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gx-12vb8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:music-note-off-2-solid" /></template>
