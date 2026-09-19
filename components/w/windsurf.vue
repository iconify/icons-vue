<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ratl6yjby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ratl6yjby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:windsurf" /></template>
