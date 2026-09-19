<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkohjf76e.css';
import '../../css/i/it25zdp1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kkohjf76e"/><path class="it25zdp1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:passenger-drinks" /></template>
