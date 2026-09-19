<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1yp1-b8j.css';
import '../../css/w/w9k2w_r8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w1yp1-b8j"/><path class="w9k2w_r8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:spell-check" /></template>
