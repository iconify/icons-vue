<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrgg98-gn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yrgg98-gn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:sunny-o" /></template>
