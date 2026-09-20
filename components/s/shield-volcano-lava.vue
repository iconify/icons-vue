<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_1r0_e_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c_1r0_e_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:shield-volcano-lava" /></template>
