<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m70qi2bva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m70qi2bva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:podium-winner" /></template>
