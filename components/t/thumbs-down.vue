<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m23rlq1om.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m23rlq1om"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:thumbs-down" /></template>
