<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdefvbo8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bdefvbo8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:point" /></template>
