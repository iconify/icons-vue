<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nko8i8blw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nko8i8blw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:spark-ar" /></template>
