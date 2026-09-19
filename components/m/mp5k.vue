<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft6uvzk5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ft6uvzk5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:mp5k" /></template>
