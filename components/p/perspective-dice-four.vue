<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5jbk3b3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s5jbk3b3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:perspective-dice-four" /></template>
