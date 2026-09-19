<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vti80kovh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vti80kovh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:plus-circle-fill-16" /></template>
