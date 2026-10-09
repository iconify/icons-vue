<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gh4i5bm1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gh4i5bm1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:star-48" /></template>
