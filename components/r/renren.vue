<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6ecf736e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="m6ecf736e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:renren" /></template>
