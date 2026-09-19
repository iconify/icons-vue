<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehuol1ywa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ehuol1ywa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:number-5-light" /></template>
