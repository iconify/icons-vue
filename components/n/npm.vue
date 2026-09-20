<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ornd7xbfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ornd7xbfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:npm" /></template>
