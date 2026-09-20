<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d80jiwb1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="d80jiwb1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:volume" /></template>
