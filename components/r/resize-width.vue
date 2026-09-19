<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqjywxbbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lqjywxbbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:resize-width" /></template>
