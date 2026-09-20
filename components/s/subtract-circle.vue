<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dch9mwb7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="dch9mwb7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:subtract-circle" /></template>
