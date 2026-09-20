<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unf88w3zv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="unf88w3zv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:percentage" /></template>
