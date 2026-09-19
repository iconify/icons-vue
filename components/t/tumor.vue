<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ej4ripj1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ej4ripj1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tumor" /></template>
