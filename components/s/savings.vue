<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wq5_vmbtx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="wq5_vmbtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:savings" /></template>
