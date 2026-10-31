<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhg5h_ghh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uhg5h_ghh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:note-sparkle-corner-fill-round" /></template>
