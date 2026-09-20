<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlyy_6c6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jlyy_6c6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:stopsign" /></template>
