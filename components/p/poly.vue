<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jajh-lbgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jajh-lbgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:poly" /></template>
