<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_pa8-b_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g_pa8-b_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:praying-mantis" /></template>
