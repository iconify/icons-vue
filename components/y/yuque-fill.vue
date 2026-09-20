<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ra53sfbgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ra53sfbgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:yuque-fill" /></template>
