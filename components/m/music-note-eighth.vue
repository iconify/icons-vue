<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qh92tebed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qh92tebed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:music-note-eighth" /></template>
