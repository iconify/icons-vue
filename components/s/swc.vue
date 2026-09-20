<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psp5wabgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="psp5wabgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:swc" /></template>
