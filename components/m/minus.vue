<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0bashbis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1408,"height":1280};
const content = `<path class="q0bashbis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:minus" /></template>
