<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-1u2acsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t-1u2acsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pokecog" /></template>
