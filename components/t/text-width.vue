<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omju9dpqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="omju9dpqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:text-width" /></template>
