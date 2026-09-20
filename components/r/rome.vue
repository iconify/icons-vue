<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycoexp6lp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ycoexp6lp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:rome" /></template>
