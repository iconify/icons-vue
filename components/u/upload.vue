<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9lqerbij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g9lqerbij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:upload" /></template>
