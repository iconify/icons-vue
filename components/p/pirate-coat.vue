<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdum_g-ri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jdum_g-ri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pirate-coat" /></template>
