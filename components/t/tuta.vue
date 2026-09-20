<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hm05gabfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hm05gabfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:tuta" /></template>
