<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ow77t97lp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ow77t97lp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:scuba-tanks" /></template>
