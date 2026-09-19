<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2a9-fy8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j2a9-fy8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sign-minus-square-bold" /></template>
