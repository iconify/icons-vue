<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gy38pybef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gy38pybef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:person-16" /></template>
