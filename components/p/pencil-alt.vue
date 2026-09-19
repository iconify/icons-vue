<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ciqmaqp1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="ciqmaqp1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:pencil-alt" /></template>
