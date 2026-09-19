<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxchkfu3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gxchkfu3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:side-panel-open-filled" /></template>
