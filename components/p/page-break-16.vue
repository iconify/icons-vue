<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9jxoghdq.css';
import '../../css/a/a12aw-hic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="c9jxoghdq"/><path class="a12aw-hic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:page-break-16" /></template>
