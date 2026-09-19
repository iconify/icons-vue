<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f85ik0b_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="f85ik0b_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:time-interval" /></template>
