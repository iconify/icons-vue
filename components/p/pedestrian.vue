<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ly82mzboj.css';
import '../../css/x/xxtpbdb0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ly82mzboj"/><path class="xxtpbdb0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:pedestrian" /></template>
