<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqxp1-bbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uqxp1-bbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:subscript" /></template>
