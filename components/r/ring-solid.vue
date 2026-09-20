<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0i8p3mks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d0i8p3mks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:ring-solid" /></template>
