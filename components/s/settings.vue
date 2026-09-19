<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4jze1rqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="y4jze1rqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:settings" /></template>
