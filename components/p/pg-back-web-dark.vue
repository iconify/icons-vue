<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujxrcqbgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ujxrcqbgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pg-back-web-dark" /></template>
