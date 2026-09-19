<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsdk4dklm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="lsdk4dklm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:question-bold" /></template>
