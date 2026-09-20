<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lz6owcb0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lz6owcb0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:panel" /></template>
