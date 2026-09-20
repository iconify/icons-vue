<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/netb8tell.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="netb8tell"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:mosque-outline" /></template>
