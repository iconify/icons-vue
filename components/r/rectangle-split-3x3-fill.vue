<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnxzphb6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="qnxzphb6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:rectangle-split-3x3-fill" /></template>
