<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugsb81byc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ugsb81byc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:microscope" /></template>
