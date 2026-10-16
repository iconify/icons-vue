<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxwuhsbvz.css';
import '../../css/n/nif5jyb9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vxwuhsbvz"/><path class="nif5jyb9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:smart-speaker-48" /></template>
