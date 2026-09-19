<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ksoy79gkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ksoy79gkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:perspective-dice-one" /></template>
