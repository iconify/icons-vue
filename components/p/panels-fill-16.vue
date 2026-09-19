<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gowmeccwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gowmeccwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:panels-fill-16" /></template>
