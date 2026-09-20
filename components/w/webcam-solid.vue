<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzuc2fb_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="uzuc2fb_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:webcam-solid" /></template>
