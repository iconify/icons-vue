<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0rmk4bdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c0rmk4bdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:user-filled" /></template>
