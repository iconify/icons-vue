<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmq9ttbfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mmq9ttbfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:star-fall4" /></template>
