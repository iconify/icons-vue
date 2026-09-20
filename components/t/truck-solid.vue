<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owo0b-9yw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="owo0b-9yw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:truck-solid" /></template>
