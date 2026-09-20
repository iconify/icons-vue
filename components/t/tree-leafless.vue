<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dv7uy3bqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dv7uy3bqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:tree-leafless" /></template>
