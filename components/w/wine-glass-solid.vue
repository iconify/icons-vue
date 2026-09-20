<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oi0e_db3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oi0e_db3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:wine-glass-solid" /></template>
