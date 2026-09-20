<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0lofy30k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f0lofy30k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:music-note-bluetooth-off" /></template>
