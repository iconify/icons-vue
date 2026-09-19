<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jy1u78bmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jy1u78bmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:waterfalls-h" /></template>
