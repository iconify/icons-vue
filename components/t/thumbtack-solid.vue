<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yp_j9ybua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yp_j9ybua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:thumbtack-solid" /></template>
