<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyus6l67b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="wyus6l67b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:yahoo" /></template>
