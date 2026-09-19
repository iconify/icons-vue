<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k99kj98ei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k99kj98ei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:straight-pipe" /></template>
