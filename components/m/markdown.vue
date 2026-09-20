<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tf6uy_bxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tf6uy_bxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:markdown" /></template>
