<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzzdn-bji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dzzdn-bji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:three-diamond-solid" /></template>
