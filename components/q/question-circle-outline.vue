<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1j67yblt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1j67yblt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:question-circle-outline" /></template>
