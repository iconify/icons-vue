<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bze383b6h.css';
import '../../css/p/ppuwdj0xa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bze383b6h"/><path class="ppuwdj0xa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:torch-48-bold" /></template>
