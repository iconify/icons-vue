<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru3rcfblm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2.5};
const content = `<path class="ru3rcfblm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:messages" /></template>
