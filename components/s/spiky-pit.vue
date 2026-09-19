<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k27mx3b-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k27mx3b-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:spiky-pit" /></template>
