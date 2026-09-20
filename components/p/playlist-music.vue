<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evn16v82j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="evn16v82j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:playlist-music" /></template>
