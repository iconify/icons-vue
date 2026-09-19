<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zb4jfgbek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zb4jfgbek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:printer" /></template>
