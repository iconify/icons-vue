<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpg-7bcoh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kpg-7bcoh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:note-sparkle-corner-round" /></template>
