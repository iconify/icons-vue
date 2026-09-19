<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zn0_a_b2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="zn0_a_b2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:qq" /></template>
