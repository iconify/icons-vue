<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8v1zhb3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="g8v1zhb3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:step-backward" /></template>
