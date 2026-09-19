<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-2lnm3ym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="i-2lnm3ym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:pushed" /></template>
