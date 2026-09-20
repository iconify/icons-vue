<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imb743brv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="imb743brv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:windsurf-light" /></template>
