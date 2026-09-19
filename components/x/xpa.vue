<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8u07bc3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m8u07bc3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:xpa" /></template>
