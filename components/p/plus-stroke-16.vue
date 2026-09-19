<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmasswbyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pmasswbyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:plus-stroke-16" /></template>
