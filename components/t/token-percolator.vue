<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6sq26k-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="e6sq26k-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:token-percolator" /></template>
