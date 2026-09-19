<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixv2spbmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ixv2spbmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:piggy-bank" /></template>
