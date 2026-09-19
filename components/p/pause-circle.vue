<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cenpm-efw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cenpm-efw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:pause-circle" /></template>
