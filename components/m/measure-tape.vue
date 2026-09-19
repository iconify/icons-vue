<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pj86w2baj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pj86w2baj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:measure-tape" /></template>
