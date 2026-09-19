<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqwivf2fv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vqwivf2fv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:octogonal-eye" /></template>
