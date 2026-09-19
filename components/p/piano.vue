<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unqi43f2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="unqi43f2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:piano" /></template>
