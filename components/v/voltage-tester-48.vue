<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7445dbmo.css';
import '../../css/c/c9yqj13fx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g7445dbmo"/><path class="c9yqj13fx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:voltage-tester-48" /></template>
