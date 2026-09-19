<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/analhzb7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="analhzb7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:owl" /></template>
