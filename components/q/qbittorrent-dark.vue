<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otypypb0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="otypypb0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:qbittorrent-dark" /></template>
