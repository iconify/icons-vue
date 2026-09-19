<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-r_n7yft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z-r_n7yft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pterodactylus" /></template>
