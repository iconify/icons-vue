<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qh005ibev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="qh005ibev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:phoneoffice" /></template>
