<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftv6d47py.css';
import '../../css/q/qy7tjby-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ftv6d47py"/><path class="qy7tjby-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:model-builder-reference" /></template>
