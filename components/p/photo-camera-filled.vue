<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qodm7xjge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qodm7xjge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:photo-camera-filled" /></template>
