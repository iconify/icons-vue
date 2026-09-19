<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cb9hdq23h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cb9hdq23h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:six-points" /></template>
