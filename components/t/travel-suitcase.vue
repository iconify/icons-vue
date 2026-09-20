<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqbzp98xj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="oqbzp98xj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:travel-suitcase" /></template>
