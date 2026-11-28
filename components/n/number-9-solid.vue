<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ug-lo7bxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ug-lo7bxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:number-9-solid" /></template>
