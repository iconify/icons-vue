<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q27t-gbcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q27t-gbcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:river" /></template>
