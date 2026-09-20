<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fllq90bkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fllq90bkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pdfmathtranslate-light" /></template>
