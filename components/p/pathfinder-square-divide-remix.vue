<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv931mb5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="pv931mb5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:pathfinder-square-divide-remix" /></template>
