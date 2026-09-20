<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptsl4jbdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ptsl4jbdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:painting-board-remix" /></template>
