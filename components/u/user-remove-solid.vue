<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5gmf2d8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w5gmf2d8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:user-remove-solid" /></template>
