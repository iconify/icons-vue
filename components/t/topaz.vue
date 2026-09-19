<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrrlo7kat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yrrlo7kat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:topaz" /></template>
