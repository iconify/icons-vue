<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g15uk9bud.css';
import '../../css/u/u-p-xwb0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g15uk9bud"/><path class="u-p-xwb0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:model-tuned" /></template>
