<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d32l00sec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="d32l00sec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:tailless-line-arrow-horizonal-scroll-remix" /></template>
