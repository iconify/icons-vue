<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njgtkipbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="njgtkipbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:mouse-pointer-square-dashed" /></template>
