<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9li6fwhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="u9li6fwhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:text-fill-12" /></template>
