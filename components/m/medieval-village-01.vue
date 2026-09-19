<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9k_imbqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m9k_imbqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:medieval-village-01" /></template>
