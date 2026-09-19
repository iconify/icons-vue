<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srv38absu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="srv38absu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:whirlpool-shuriken" /></template>
