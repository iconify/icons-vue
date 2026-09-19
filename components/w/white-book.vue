<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0c-0xbuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n0c-0xbuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:white-book" /></template>
