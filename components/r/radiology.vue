<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2x7t-b5p.css';
import '../../css/i/i9nyku57s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="v2x7t-b5p"/><path class="i9nyku57s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:radiology" /></template>
