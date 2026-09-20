<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tk6_03hfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tk6_03hfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:place-of-worship-building" /></template>
