<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5h7uud-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5h7uud-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:text-description" /></template>
