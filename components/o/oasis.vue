<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yss1rp-_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yss1rp-_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:oasis" /></template>
