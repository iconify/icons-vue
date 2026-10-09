<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3w_jjzoh.css';
import '../../css/f/fu6xpoo5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l3w_jjzoh"/><path class="fu6xpoo5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:undo-48-bold" /></template>
