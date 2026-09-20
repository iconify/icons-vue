<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpy40urxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zpy40urxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:view-files-24" /></template>
