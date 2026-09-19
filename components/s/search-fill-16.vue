<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w__re01gs.css';
import '../../css/c/ctx28g1ir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<circle class="w__re01gs"/><path class="ctx28g1ir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:search-fill-16" /></template>
