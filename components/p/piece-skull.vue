<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p44ng8ujk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p44ng8ujk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:piece-skull" /></template>
