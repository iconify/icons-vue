<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qb_el90_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qb_el90_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:tooth" /></template>
