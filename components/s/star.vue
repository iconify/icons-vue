<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnzw39bif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pnzw39bif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="doodle-icons:star" /></template>
