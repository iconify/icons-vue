<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ze43ctp2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ze43ctp2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:spoon" /></template>
