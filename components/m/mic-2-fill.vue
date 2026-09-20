<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cenhc-zoe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cenhc-zoe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:mic-2-fill" /></template>
