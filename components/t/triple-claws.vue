<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjd1sol1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mjd1sol1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:triple-claws" /></template>
