<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-m3seolj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="x-m3seolj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:volume-off" /></template>
