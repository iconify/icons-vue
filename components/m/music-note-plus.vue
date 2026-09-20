<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rw72m4boy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rw72m4boy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:music-note-plus" /></template>
