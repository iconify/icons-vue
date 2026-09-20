<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7npn_d3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="d7npn_d3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:treasure-chest-remix" /></template>
