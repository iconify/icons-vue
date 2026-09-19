<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqoj1wbvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="kqoj1wbvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:temperature" /></template>
