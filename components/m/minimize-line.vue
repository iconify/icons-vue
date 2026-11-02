<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zkg31wasg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zkg31wasg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:minimize-line" /></template>
