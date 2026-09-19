<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xeb16tbab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="xeb16tbab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:outdent" /></template>
