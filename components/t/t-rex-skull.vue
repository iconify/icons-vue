<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/is9u0rkgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="is9u0rkgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:t-rex-skull" /></template>
