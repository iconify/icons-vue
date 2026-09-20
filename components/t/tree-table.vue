<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbwtn-biq.css';
import '../../css/e/e7ttr_boe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gbwtn-biq"/><path class="e7ttr_boe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:tree-table" /></template>
