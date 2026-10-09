<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvg3fbb0b.css';
import '../../css/l/l7hgfejkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bvg3fbb0b"/><path class="l7hgfejkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:reply-48-bold" /></template>
