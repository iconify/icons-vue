<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3unbqbly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o3unbqbly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:prisoner" /></template>
