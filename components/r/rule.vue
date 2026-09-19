<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bg4u3kb1v.css';
import '../../css/e/ey3vbs2kb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bg4u3kb1v"/><path class="ey3vbs2kb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:rule" /></template>
