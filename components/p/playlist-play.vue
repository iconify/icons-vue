<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obf8cbbsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="obf8cbbsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:playlist-play" /></template>
