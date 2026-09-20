<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzguzc2ed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tzguzc2ed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:psyarxiv" /></template>
