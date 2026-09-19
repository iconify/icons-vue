<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjkb6mbzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pjkb6mbzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:swimfins" /></template>
