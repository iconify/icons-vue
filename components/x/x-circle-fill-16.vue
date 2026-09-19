<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxw1wac_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uxw1wac_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:x-circle-fill-16" /></template>
