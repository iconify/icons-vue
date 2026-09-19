<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8455lb4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d8455lb4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:table-tennis-paddle-ball" /></template>
