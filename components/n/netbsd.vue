<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eelz5c2dj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eelz5c2dj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:netbsd" /></template>
