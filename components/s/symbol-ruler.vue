<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0pp-x5gd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q0pp-x5gd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:symbol-ruler" /></template>
