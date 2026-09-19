<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbdq3lbhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dbdq3lbhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:menhir" /></template>
