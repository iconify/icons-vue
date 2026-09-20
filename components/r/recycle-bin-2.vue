<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7-aj4bpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="g7-aj4bpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:recycle-bin-2" /></template>
