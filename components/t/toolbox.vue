<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyu6yccrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dyu6yccrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:toolbox" /></template>
