<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8ug4ybrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="y8ug4ybrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:up-long" /></template>
