<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfkdut3no.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yfkdut3no"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:sort-asc-16" /></template>
