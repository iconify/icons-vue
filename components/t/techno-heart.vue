<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wb4t3pbgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wb4t3pbgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:techno-heart" /></template>
