<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjom0ukgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cjom0ukgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sun-priest" /></template>
