<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/squnhsb2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":224,"height":224};
const content = `<path class="squnhsb2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:rust-dark" /></template>
