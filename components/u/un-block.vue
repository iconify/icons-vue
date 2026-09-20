<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/do5d53btf.css';
import '../../css/j/j6h5hmb5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="do5d53btf"/><path class="j6h5hmb5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:un-block" /></template>
