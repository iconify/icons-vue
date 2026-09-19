<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zb6oplr4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zb6oplr4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:mole" /></template>
