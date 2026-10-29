<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ribff0qeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ribff0qeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:rotate-cw-solid" /></template>
