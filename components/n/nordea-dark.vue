<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czvq_1biq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1515,"height":1477};
const content = `<path class="czvq_1biq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:nordea-dark" /></template>
