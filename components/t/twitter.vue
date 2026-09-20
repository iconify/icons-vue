<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d24y88b6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":209};
const content = `<path class="d24y88b6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:twitter" /></template>
