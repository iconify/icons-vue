<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1_al-bcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="x1_al-bcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:planetscale-light" /></template>
