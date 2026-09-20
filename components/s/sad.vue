<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5c6_gbgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="s5c6_gbgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:sad" /></template>
