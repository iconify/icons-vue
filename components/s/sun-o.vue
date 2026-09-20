<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ck7oek4jj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ck7oek4jj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:sun-o" /></template>
