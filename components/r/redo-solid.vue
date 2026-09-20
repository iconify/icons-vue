<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5wuqj8_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j5wuqj8_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:redo-solid" /></template>
