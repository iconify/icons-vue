<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_kk48bqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1023};
const content = `<path class="r_kk48bqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:playstore" /></template>
