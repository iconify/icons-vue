<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_g4o-8ic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y_g4o-8ic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:scroll-lock-16" /></template>
