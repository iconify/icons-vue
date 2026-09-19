<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgrd-mbwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pgrd-mbwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:troll" /></template>
