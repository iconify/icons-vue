<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n11l6w7ir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n11l6w7ir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:staircase" /></template>
