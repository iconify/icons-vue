<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ye3j8cb9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ye3j8cb9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:remark" /></template>
