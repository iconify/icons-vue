<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r49rvebmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r49rvebmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:messages-square-fill" /></template>
