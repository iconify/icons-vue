<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wh01m4neq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wh01m4neq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:music-note-slider-outline" /></template>
