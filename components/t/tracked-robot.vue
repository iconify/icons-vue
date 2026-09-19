<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3wig2b0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c3wig2b0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tracked-robot" /></template>
