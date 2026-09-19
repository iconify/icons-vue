<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ex-4i4b2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":408,"height":408};
const content = `<path class="ex-4i4b2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:videocam-off" /></template>
