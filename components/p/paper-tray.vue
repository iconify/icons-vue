<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2z9wcbok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x2z9wcbok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:paper-tray" /></template>
