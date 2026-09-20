<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2n_oixhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2n_oixhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:message-reply-glyph" /></template>
