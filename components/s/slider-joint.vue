<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_l44cbhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u_l44cbhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:slider-joint" /></template>
