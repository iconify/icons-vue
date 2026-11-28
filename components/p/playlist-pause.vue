<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xd1roxm6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xd1roxm6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:playlist-pause" /></template>
