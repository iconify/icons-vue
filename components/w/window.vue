<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whl0o8ody.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="whl0o8ody"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:window" /></template>
