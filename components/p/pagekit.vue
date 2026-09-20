<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vsmt7b2xl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vsmt7b2xl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:pagekit" /></template>
