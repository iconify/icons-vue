<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qt62stbxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qt62stbxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:wind-slap" /></template>
