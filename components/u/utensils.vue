<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypewuccyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ypewuccyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:utensils" /></template>
