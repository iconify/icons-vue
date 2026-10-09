<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5pljbc4p.css';
import '../../css/s/s5hz1qbpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w5pljbc4p"/><path class="s5hz1qbpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:torch-20" /></template>
