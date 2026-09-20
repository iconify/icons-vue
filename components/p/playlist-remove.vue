<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ct0rwgbmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ct0rwgbmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:playlist-remove" /></template>
