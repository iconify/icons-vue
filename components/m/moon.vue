<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gg-aufe2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="gg-aufe2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:moon" /></template>
