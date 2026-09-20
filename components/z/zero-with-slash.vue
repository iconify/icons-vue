<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wk-w0bb5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wk-w0bb5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:zero-with-slash" /></template>
