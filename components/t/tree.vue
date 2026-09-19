<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/on8zofbrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="on8zofbrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:tree" /></template>
