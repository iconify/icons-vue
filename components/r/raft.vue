<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uf9xhl_nm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uf9xhl_nm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:raft" /></template>
