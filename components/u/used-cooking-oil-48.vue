<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqiw7wq1k.css';
import '../../css/u/u_7j5cbnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xqiw7wq1k"/><path class="u_7j5cbnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:used-cooking-oil-48" /></template>
