<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-iqkzb1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="c-iqkzb1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:person-walking-arrow-right" /></template>
