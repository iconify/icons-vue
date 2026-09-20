<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqep6zwwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uqep6zwwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:star" /></template>
