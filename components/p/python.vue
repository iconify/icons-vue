<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/te-hy03mo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="te-hy03mo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:python" /></template>
