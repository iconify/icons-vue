<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ee5gdzt4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ee5gdzt4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:rogue" /></template>
