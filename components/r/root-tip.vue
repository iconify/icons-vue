<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ax5x1zbwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ax5x1zbwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:root-tip" /></template>
