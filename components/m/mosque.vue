<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqzen09ml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vqzen09ml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:mosque" /></template>
