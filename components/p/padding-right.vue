<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkncb7blc.css';
import '../../css/y/y_guo854f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vkncb7blc"/><path class="y_guo854f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:padding-right" /></template>
