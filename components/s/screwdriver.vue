<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vu4e92lgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vu4e92lgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:screwdriver" /></template>
