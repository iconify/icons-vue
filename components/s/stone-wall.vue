<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7548ubys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v7548ubys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:stone-wall" /></template>
