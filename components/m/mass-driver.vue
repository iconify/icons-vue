<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/as6chiboe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="as6chiboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:mass-driver" /></template>
