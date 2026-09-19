<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqqsoly8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="uqqsoly8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:mendeley" /></template>
