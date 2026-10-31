<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jztn7z8ge.css';
import '../../css/x/x47r2-ccs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="jztn7z8ge"/><path class="x47r2-ccs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:south-american-union" /></template>
