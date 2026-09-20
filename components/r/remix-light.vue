<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uw-9bxhcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":297};
const content = `<path class="uw-9bxhcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:remix-light" /></template>
