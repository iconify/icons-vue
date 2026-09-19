<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8ev30b2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h8ev30b2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:windchimes" /></template>
