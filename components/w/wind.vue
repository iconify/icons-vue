<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft66pcbfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ft66pcbfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:wind" /></template>
