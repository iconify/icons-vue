<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0y-h_16m.css';
import '../../css/k/ke0zg7b_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x0y-h_16m"/><path class="ke0zg7b_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:palm-urban-tree-pot" /></template>
