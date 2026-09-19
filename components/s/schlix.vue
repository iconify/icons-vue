<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n55t4cb-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="n55t4cb-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:schlix" /></template>
