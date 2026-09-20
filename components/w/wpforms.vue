<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ub0qy8b0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ub0qy8b0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:wpforms" /></template>
