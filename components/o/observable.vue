<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/so0zkobyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="so0zkobyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:observable" /></template>
