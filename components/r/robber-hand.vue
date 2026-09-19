<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-uydrm2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y-uydrm2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:robber-hand" /></template>
