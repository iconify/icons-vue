<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxf_ij_3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bxf_ij_3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:suspicious" /></template>
