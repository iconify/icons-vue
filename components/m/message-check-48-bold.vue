<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zy-u42bhp.css';
import '../../css/b/bkoar43ua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zy-u42bhp"/><path class="bkoar43ua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:message-check-48-bold" /></template>
