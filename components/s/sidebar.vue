<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmyxf7b4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mmyxf7b4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:sidebar" /></template>
