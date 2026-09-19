<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rij442pdg.css';
import '../../css/m/mbirz4byx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rij442pdg"/><path class="mbirz4byx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:square-plus" /></template>
