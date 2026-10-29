<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdwgb8ufi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdwgb8ufi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:pill-solid" /></template>
