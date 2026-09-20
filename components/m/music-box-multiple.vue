<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgup0bcsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgup0bcsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:music-box-multiple" /></template>
