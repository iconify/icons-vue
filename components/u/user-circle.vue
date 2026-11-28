<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqw14dbpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zqw14dbpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:user-circle" /></template>
