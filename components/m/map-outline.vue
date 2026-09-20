<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g55q6onat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g55q6onat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:map-outline" /></template>
