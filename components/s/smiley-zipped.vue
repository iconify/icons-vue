<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ky8c2yxsy.css';
import '../../css/o/oy5x1vbap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ky8c2yxsy"/><path class="oy5x1vbap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:smiley-zipped" /></template>
