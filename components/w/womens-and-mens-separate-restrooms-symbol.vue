<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amsqombxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="amsqombxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:womens-and-mens-separate-restrooms-symbol" /></template>
