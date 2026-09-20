<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmd4-hb4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zmd4-hb4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:time-o" /></template>
