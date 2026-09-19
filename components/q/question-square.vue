<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfd1qnxoq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="rfd1qnxoq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:question-square" /></template>
