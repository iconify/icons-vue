<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ziyyuibot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="ziyyuibot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:phone-portrait" /></template>
