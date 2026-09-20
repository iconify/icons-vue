<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uq4ay1j3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uq4ay1j3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:minus-circle-solid" /></template>
