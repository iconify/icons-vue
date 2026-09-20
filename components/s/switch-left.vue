<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_3us-pxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-5};
const content = `<path class="w_3us-pxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:switch-left" /></template>
