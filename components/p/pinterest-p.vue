<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iuew-5_qh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1280,"height":1664};
const content = `<path class="iuew-5_qh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:pinterest-p" /></template>
