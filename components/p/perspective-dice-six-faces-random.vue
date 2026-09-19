<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6hl0kb_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f6hl0kb_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:perspective-dice-six-faces-random" /></template>
