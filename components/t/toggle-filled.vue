<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6-x6hoxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="m6-x6hoxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:toggle-filled" /></template>
