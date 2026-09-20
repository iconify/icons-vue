<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hq6rqbp0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="hq6rqbp0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:power-on-symbol" /></template>
