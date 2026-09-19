<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vel8po25y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vel8po25y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:reptile-tail" /></template>
