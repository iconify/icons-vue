<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfftsmbos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="bfftsmbos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:table-top-horizontal-stairs-ascend-right" /></template>
