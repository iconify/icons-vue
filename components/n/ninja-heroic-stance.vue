<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9-dgebld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j9-dgebld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ninja-heroic-stance" /></template>
