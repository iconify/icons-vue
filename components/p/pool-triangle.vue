<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c680_fk7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c680_fk7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pool-triangle" /></template>
