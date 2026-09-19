<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqv5abcjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":376,"height":384};
const content = `<path class="wqv5abcjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:zoom-in" /></template>
