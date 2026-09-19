<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9mj_4bsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u9mj_4bsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:thunder-skull" /></template>
