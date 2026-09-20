<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbivq1bzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hbivq1bzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:music-note-variant-filled" /></template>
