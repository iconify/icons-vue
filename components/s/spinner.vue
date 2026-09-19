<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fw8dmrebl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1728};
const content = `<path class="fw8dmrebl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:spinner" /></template>
