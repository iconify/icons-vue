<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5g9_vn4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y5g9_vn4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:meeting-plus" /></template>
