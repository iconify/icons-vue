<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhe6x9bga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nhe6x9bga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:target-prize" /></template>
