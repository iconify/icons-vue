<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iea4ydfqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iea4ydfqj primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:number-7-duotone" /></template>
