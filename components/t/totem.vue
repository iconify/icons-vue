<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8m4odqkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w8m4odqkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:totem" /></template>
