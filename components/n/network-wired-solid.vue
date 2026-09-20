<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tiwx7ab7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tiwx7ab7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:network-wired-solid" /></template>
