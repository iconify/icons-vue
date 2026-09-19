<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6d9-abro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v6d9-abro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:star-skull" /></template>
