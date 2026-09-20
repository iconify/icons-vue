<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zs16nnbug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zs16nnbug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:packt" /></template>
