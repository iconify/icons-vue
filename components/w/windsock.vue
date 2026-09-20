<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jft04mbyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jft04mbyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:windsock" /></template>
