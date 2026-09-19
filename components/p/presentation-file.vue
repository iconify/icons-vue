<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzhvztb2z.css';
import '../../css/q/q44zm2bli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pzhvztb2z"/><path class="q44zm2bli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:presentation-file" /></template>
