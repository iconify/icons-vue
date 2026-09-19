<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fuledfb3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fuledfb3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:music-note-add" /></template>
