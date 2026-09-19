<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vu3v6tmeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":192,"height":512};
const content = `<path class="vu3v6tmeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:male" /></template>
