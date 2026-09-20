<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ms2x3t45m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ms2x3t45m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:middle-finger-fill" /></template>
