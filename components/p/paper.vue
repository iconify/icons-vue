<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y64d-bcld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y64d-bcld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:paper" /></template>
