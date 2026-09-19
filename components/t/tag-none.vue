<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-89v3b5b.css';
import '../../css/f/fjhdmsv1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k-89v3b5b"/><path class="fjhdmsv1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:tag-none" /></template>
