<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbyolzb7w.css';
import '../../css/b/byv6wwb2b.css';
import '../../css/r/rv2qj4l3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cbyolzb7w"/><path class="byv6wwb2b"/><path class="rv2qj4l3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pig-20-bold" /></template>
