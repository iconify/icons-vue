<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nllsco9uf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nllsco9uf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:quadrilateral" /></template>
