<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hc6br1bwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hc6br1bwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tentacle-heart" /></template>
