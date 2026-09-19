<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gte8b1byc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gte8b1byc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:tungsten-light" /></template>
