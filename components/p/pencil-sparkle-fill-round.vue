<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/it00rbcjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="it00rbcjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pencil-sparkle-fill-round" /></template>
