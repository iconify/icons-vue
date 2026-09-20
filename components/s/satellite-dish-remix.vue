<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umfba3b2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="umfba3b2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:satellite-dish-remix" /></template>
