<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zusud2met.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zusud2met"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:sum" /></template>
