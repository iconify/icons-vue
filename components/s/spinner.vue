<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_-n7mbal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h_-n7mbal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:spinner" /></template>
