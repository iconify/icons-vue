<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gile7j0jo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="gile7j0jo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:payload-cms-light" /></template>
