<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zuvh--brb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zuvh--brb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:twitch-line" /></template>
