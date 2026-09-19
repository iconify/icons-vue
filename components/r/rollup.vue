<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iml59opdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":387,"height":512};
const content = `<path class="iml59opdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:rollup" /></template>
