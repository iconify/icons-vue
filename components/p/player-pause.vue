<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xa3lzv8-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xa3lzv8-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:player-pause" /></template>
