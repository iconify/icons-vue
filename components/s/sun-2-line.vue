<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdis0vbxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jdis0vbxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sun-2-line" /></template>
