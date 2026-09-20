<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1b1a9bhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r1b1a9bhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:power-socket-canada" /></template>
