<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5_ov5lgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="c5_ov5lgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:paint-bucket" /></template>
