<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vobx_nbbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vobx_nbbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:space-suit" /></template>
