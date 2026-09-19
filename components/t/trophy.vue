<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l50riizbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l50riizbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:trophy" /></template>
