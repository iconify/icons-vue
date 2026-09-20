<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3o-d3q7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-3,"top":-2};
const content = `<path class="f3o-d3q7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:mic-alt" /></template>
