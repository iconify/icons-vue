<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thz6gtmay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thz6gtmay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-2-fill" /></template>
