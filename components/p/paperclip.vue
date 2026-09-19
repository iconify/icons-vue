<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dd6o0qbzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dd6o0qbzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:paperclip" /></template>
