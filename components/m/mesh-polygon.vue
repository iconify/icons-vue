<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-lk33bma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f-lk33bma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:mesh-polygon" /></template>
