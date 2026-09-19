<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qi0x6kbbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qi0x6kbbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ship-bow" /></template>
