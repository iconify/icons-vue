<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1muyrb2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="u1muyrb2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:person-arrow-down-to-line" /></template>
