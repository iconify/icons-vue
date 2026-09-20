<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw9ju4b-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="zw9ju4b-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:minus" /></template>
