<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4i273b2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y4i273b2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:panorama-horizontal" /></template>
