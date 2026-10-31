<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfyxu1xww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sfyxu1xww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:music-note-sparkle-round" /></template>
