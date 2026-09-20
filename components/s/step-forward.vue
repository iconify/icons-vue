<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wh4r42bvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wh4r42bvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:step-forward" /></template>
