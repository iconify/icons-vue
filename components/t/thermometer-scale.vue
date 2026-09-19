<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6eu1pbka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v6eu1pbka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:thermometer-scale" /></template>
