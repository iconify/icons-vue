<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9bol95zl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9bol95zl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:printer-x" /></template>
