<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/po7c3mbcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="po7c3mbcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ship-wreck" /></template>
