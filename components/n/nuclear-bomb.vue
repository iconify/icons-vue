<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqv43tb6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uqv43tb6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:nuclear-bomb" /></template>
