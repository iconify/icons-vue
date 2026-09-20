<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-8at39gu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="m-8at39gu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:two-people-standing-in-rectangle-outline-under-arrow-up-beside-arrow-down" /></template>
