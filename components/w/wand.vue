<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifdnxp4wp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ifdnxp4wp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:wand" /></template>
