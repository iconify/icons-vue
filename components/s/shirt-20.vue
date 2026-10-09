<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/osewcubls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="osewcubls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:shirt-20" /></template>
