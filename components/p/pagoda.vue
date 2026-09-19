<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m160mtbnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m160mtbnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pagoda" /></template>
