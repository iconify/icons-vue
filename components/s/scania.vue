<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajjt2vrag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ajjt2vrag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:scania" /></template>
