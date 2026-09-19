<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e96ji41bl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e96ji41bl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pumpkin-mask" /></template>
