<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvnte8biv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xvnte8biv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:ruler" /></template>
