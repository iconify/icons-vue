<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxn6f5kct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="dxn6f5kct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:present" /></template>
