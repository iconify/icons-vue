<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zo_ii94vh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zo_ii94vh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:user-check" /></template>
