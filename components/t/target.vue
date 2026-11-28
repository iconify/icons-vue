<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pyf7gmbzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pyf7gmbzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:target" /></template>
