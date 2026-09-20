<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysms35bwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ysms35bwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:sphere" /></template>
