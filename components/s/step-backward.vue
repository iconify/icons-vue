<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_z6oabmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_z6oabmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:step-backward" /></template>
