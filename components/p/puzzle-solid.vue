<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-7b7dbjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-7b7dbjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:puzzle-solid" /></template>
