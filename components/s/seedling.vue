<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfk20ob_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lfk20ob_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:seedling" /></template>
