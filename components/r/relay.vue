<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-l3fcbld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-l3fcbld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:relay" /></template>
