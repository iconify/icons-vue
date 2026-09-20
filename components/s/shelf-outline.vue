<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdggi4wlu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jdggi4wlu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:shelf-outline" /></template>
