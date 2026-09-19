<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ii7da9b0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ii7da9b0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:palm-tree" /></template>
