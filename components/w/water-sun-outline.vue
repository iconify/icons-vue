<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjp5pxv8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xjp5pxv8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:water-sun-outline" /></template>
