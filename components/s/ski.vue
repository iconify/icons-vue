<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rufqdqr3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="rufqdqr3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:ski" /></template>
