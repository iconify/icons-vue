<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1e6a6b7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q1e6a6b7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:stick-splitting" /></template>
