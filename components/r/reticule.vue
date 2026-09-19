<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evs4fibve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="evs4fibve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:reticule" /></template>
