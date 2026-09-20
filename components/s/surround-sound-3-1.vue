<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwh6emb2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kwh6emb2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:surround-sound-3-1" /></template>
