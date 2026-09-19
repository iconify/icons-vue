<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmuj8wb5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lmuj8wb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:work" /></template>
