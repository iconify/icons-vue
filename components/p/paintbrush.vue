<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3pkl-tvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h3pkl-tvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:paintbrush" /></template>
