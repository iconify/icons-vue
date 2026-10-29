<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ik4-3--mh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ik4-3--mh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:text-cursor-solid" /></template>
