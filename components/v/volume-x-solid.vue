<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cc9lbspxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cc9lbspxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:volume-x-solid" /></template>
