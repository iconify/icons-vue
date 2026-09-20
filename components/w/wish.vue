<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vd2wd4blj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vd2wd4blj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:wish" /></template>
