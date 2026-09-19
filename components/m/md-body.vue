<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ia6mv6bai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ia6mv6bai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-body" /></template>
