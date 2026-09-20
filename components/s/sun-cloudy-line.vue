<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eoe905xwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eoe905xwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:sun-cloudy-line" /></template>
