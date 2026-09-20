<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3me3zb-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j3me3zb-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:searchengin" /></template>
