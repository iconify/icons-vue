<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r82rz7l0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r82rz7l0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:watch" /></template>
