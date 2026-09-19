<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqix6e-9e.css';
import '../../css/r/rauwxcb1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qqix6e-9e"/><path class="rauwxcb1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:volume-block-storage" /></template>
