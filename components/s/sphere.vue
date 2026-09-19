<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cu1_sz9lp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cu1_sz9lp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:sphere" /></template>
