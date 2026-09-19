<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdytr4pqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jdytr4pqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:storage" /></template>
