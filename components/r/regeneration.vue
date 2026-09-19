<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdc22dbum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cdc22dbum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:regeneration" /></template>
