<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcomewbtu.css';
import '../../css/m/mpg7plbez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer pcomewbtu"/><path class="duoicon-primary-layer mpg7plbez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:message" /></template>
