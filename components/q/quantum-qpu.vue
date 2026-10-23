<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uuln7pb0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uuln7pb0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:quantum-qpu" /></template>
