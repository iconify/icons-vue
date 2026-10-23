<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gb2c95t9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gb2c95t9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:saudi-riyal" /></template>
