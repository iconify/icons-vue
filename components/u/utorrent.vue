<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8gd5xbhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n8gd5xbhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:utorrent" /></template>
