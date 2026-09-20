<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xv05p5bjy.css';
import '../../css/z/zu9zkld_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xv05p5bjy"/><path clip-rule="evenodd" class="zu9zkld_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:save-all-16" /></template>
