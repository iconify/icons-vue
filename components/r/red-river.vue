<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mki427-cd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="mki427-cd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:red-river" /></template>
