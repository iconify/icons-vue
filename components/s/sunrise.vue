<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4jjlvb0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u4jjlvb0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:sunrise" /></template>
