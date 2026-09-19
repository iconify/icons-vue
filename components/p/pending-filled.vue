<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yr72fibsk.css';
import '../../css/v/v3y0e9ubk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yr72fibsk"/><path class="v3y0e9ubk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:pending-filled" /></template>
