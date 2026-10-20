<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0s85yyfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i0s85yyfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:option-key-48-bold" /></template>
