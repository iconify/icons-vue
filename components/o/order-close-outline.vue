<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_mclbccr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o_mclbccr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:order-close-outline" /></template>
