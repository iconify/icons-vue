<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d67njf0pn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="d67njf0pn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:openfeature-dark" /></template>
