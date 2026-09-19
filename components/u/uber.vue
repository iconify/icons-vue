<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dddisgzym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b dddisgzym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:uber" /></template>
