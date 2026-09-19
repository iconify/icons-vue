<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jp_tt3b4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jp_tt3b4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:moon-orbit" /></template>
