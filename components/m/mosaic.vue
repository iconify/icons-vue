<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtry4db9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mtry4db9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:mosaic" /></template>
