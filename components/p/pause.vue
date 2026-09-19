<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dou8j9b6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dou8j9b6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:pause" /></template>
