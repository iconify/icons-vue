<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cg2rt9b6k.css';
import '../../css/i/i7oy_ep3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cg2rt9b6k"/><path class="i7oy_ep3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pen-20-bold" /></template>
