<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnp27ng5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xnp27ng5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:south-korea" /></template>
