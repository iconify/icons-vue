<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfe581dxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kfe581dxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:suitcase" /></template>
