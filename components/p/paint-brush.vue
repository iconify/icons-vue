<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oot8nnbci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oot8nnbci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:paint-brush" /></template>
