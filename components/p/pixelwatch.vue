<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijqx54bau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijqx54bau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:pixelwatch" /></template>
