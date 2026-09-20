<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6xjq6btb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u6xjq6btb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:scilab" /></template>
