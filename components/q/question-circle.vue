<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/ba7_2s_nj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ba7_2s_nj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:question-circle" /></template>
