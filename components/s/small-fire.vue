<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/af8sc-fzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="af8sc-fzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:small-fire" /></template>
