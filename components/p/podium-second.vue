<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gejc2klfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gejc2klfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:podium-second" /></template>
