<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_ghg35vl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t_ghg35vl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:popcorn" /></template>
