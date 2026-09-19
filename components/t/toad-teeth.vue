<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z66tl_b8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z66tl_b8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:toad-teeth" /></template>
