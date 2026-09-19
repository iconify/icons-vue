<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nm0r1bb0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nm0r1bb0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tarot-15-the-devil" /></template>
