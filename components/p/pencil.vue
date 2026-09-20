<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylq7u89oc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ylq7u89oc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:pencil" /></template>
