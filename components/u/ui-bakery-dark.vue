<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_jzqe7zd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y_jzqe7zd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ui-bakery-dark" /></template>
