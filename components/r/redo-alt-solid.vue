<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dak5-acry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dak5-acry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:redo-alt-solid" /></template>
