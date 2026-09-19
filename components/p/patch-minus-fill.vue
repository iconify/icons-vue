<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opnm4c39e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="opnm4c39e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:patch-minus-fill" /></template>
