<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6tv-82-z.css';
import '../../css/u/uufe-4b8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i6tv-82-z"/><path class="uufe-4b8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:view-next" /></template>
