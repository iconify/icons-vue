<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b43v05bxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b43v05bxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:radar-enhanced" /></template>
