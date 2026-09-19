<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3e5x1bam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u3e5x1bam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:meeple" /></template>
