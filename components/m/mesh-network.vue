<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avwjq7blo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="avwjq7blo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:mesh-network" /></template>
