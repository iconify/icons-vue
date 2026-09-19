<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvi8pxblc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qvi8pxblc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:phone-disabled" /></template>
