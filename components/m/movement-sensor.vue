<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iszta5b5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iszta5b5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:movement-sensor" /></template>
