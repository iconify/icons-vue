<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clcn2dq2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1550,"height":1000};
const content = `<path class="clcn2dq2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:reply-all" /></template>
