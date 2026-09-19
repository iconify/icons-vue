<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1uq2-bld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o1uq2-bld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:outdoor" /></template>
