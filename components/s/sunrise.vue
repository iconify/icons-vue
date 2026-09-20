<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hb_t3abty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="hb_t3abty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:sunrise" /></template>
