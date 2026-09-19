<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjdbqjbhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zjdbqjbhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:walk" /></template>
