<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orby3sqlt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="orby3sqlt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:time-lapse-remix" /></template>
