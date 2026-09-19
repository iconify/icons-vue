<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tl4tf0b_w.css';
import '../../css/z/z916qcbra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tl4tf0b_w"/><path class="z916qcbra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:save-model" /></template>
