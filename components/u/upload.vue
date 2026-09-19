<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljgerfk3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ljgerfk3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:upload" /></template>
