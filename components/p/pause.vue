<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1_5a4buf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p1_5a4buf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:pause" /></template>
