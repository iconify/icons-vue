<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yb-2542dh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="yb-2542dh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:true" /></template>
