<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_p-1bobd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u_p-1bobd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:star-formation" /></template>
